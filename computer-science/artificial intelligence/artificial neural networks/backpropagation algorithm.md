in machine learning backpropagation is a widely used [[algorithm]] for training feedforward  [[artificial neural network]]s and for functions generally

in fitting a neural network, the algorithm computes the gradient  of the loss function with respect to the weights of the network for a single input-output example by using the [[chain rule]], computing the gradient one layer at a time, iterating backwards from the last layer

##### notation and motivation
taking into account that,  we denote:
- $x$: the input ([[vector]] of features)
- $y$: target output
- $C$ [[cost function]]
- $L$: number of layers
- $W^l=(w^l_{jk})$ : weights between layer $l-1$ and $l$, where $w^l_{jk}$ is the weight between the $k$-th node in the layer $l-1$ and  the $j$-th node on layer $l$
- $f^l$: [[activation function]]s at $l$

the overall network can be defined as a combination of [[function composition]] and [[matrix multiplication]]:
$$g(x):=f^L(W^Lf^{L-1}(W^{L-1}f^{L-2}(\ldots f^1(W^1x)\ldots)))$$
for a training [[set]] there will be a set of input output pairs $\{(x_i,y_i)\}$
for each input-output pair $(x_i,y_i)$ in the training set, the loss of the model on that pair is the cost of the difference between the predicted output $g(x_i)$ and the target output $y_i$
$$C(y_i,g(x_i))$$
backpropagation computes the gradient for a fixed input output pair where the weights can vary
each individual component of the gradient can be computed by the chain rule: however, doing this separately for each weight is highly inefficient, thus the algorithm is brought into play

informally, the point is that since the only way a weight in $W^1$ affects the loss is through its effect on the next layer and it does so linearly, $\delta^l$ are the only data needed to compute the gradients of the weights at layer $l$, and then the previous layer $\delta^{-1}$ can be computed and so on recursively
this avoids inefficiency in two ways:
- it avoids duplication
- it avoids unnecessary intermediate calculations
backpropagation can be expressed formally in terms of [[matrix multiplication]] 

##### general algorithm
- error at the output layer is calculated$$\delta^l=\frac{\partial E}{\partial o_j} \frac{\partial o_j}{\partial net_j}$$
-   error is retropropagated to the previous layer
$$\delta^{l-1} = $$
- partial derivatives are calculated using the error obtained$$\frac{\partial E}{\partial w}=\delta^{l-1}o^{l-2}$$

##### formalised definition
for each neuron $j$, its output $o_j$ is defined as 
$o_j=\varphi(net_j) = \varphi(\sum^n_{k=1}w_{kj}o_k)$ 
where the [[activation function]] $\varphi$ is a non-linear[^1] and [[differentiable function]] 

the input $net_j$ is the weighted sum of outputs $o_k$ of previous neurons

if the neuron is in the first layer after the input layer, the $o_k$ are simply the inputs $x_k$ to the network
the number of input units to the neuron is $n$ 
the variable $w_{kj}$ denotes the weight between the neuron $k$ of the previous layer and neuron $j$ of the current layer

###### output layer
the error on a given neuron $j$ may be defined as the result of the function cost applied to the result of applying the  [[activation function]] to $net_j$ 
$$E = C(f(net_j))$$
thus, $E$ is the result of a [[function composition]] of the function cost with the activation function over the weighted sum of the inputs on the neuron[^2]
the [[partial derivative]] of the error with respect to a weight $w_{ij}$ is done using the [[chain rule]] twice:
$$\frac{\partial E}{\partial w_{wij}} = \frac{\partial E}{\partial o_j}\frac{\partial o_j}{\partial w_{wij}}= \frac{\partial E}{\partial o_j}\frac{\partial o_j}{\partial net_j}\frac{\partial net_j}{\partial w_{ij}}$$
- in the first parameter $\frac{\partial E}{\partial o_j}$, the partial derivative of the error for small modifications of the output, since we are on the last layer, this implies comparing the output of the neural network itself to the desired output
  
	given the median square error $C(o_j) = \frac{1}{2}\sum_j(o_j-y_j)^2$, we get that$$\frac{\partial E}{\partial o_j} = (o_j-y_j)$$
- in the second parameter, $\frac{\partial o_j}{\partial net_j}$ the value obtained will be the change on the output for a change on the weighted sum calculated on the node, thus, this calculation implies the derivative of the activation function

	- the partial derivative result of the two first parameters  $\frac{\partial E}{\partial o_j}\frac{\partial o_j}{\partial net_j} = \frac{\partial E}{\partial net_j}$  denoted generally as $\delta_j$, determines the change of the error by variations on the change of the weighted sum of the neuron, that is, if the result of this derivative is big, we can conclude that this neuron plays an important role on determining the error

- in the last factor,  only one  term in the sum $net_j$ depends on $w_{ij}$, so that
$$\frac{\partial net_j}{\partial w_{ij}} = \frac{\partial}{\partial w_{ij}}\Big(\sum^n_{k=1}w_{kj}o_k\Big) =\frac{\partial}{\partial w_{ij}}w_{ij}o_i=o_i$$
taking into account all of this, the  initial derivative can be now expressed as:$$\frac{\partial E}{\partial w_{ij}}= \delta_j o_i$$
that is, the partial derivative of the error can be obtained as the error on each neuron times the error on the previous layer

moreover, the error on the output layer must be modified
to update the weight $w_{ij}$ using [[gradient descent]], one must choose a learning rate $\mu > 0$
the change in weight needs to reflect the impact on $E$
- if $\frac{\partial E}{\partial w_{ij}} > 0$ an increase in $w_{ij}$ increases $E$
- if $\frac{\partial E}{\partial w_{ij}} < 0$ an increase in $w_{ij}$ decreases $E$
the new $\Delta w_{ij}$ is added to the old weight[^3]
$$\Delta w_{ij}=-\mu\frac{\partial E}{\partial w_{ij}} = -\mu o_i\delta_j$$

###### hidden layer
- the fist parameter $\frac{\partial E}{\partial o_j}$ becomes less obvious
  considering $E$ as a function with the inputs being all neurons $L=\{u,v,\ldots,w\}$, receiving input from neuron $j$$$\frac{\partial E}{\partial o_j} = \frac{\partial E(net_u,net_v\ldots,net_w)}{\partial o_j}$$and taking the [[derivative]] with respect to $o_j$$$\frac{\partial E}{\partial o_j}=\sum_{l\in L}\Big(\frac{\partial E}{\partial net_l}\frac{\partial net_l}{\partial o_l}\Big) =\sum_{l\in L}\Big(\frac{\partial E}{\partial o_l}\frac{\partial o_l}{\partial net_l}\frac{\partial net_l}{\partial o_l}\Big)=\sum_{l\in L}\Big(\frac{\partial E}{\partial o_l}\frac{\partial o_l}{\partial net_l}w_{jl}\Big)$$
  - the other two parameters can be calculated as before

thus, in the case of a hidden layer, the definition of $\delta^l=\frac{\partial E}{\partial o_j} \frac{\partial o_j}{\partial net_j}$  is modified:$$\delta_j =\Big(\sum_{l\in L}w_{jl}\delta_l\Big) \frac{\partial net_l}{\partial net_j}$$


[^1]: the derivative of the activation function is needed in order to calculate the variation of the error (the [[ReLU]] is a special case, not a [[differentiable function]] at a certain point)

[^2]: note that this could also be applied to $C$, the cost function itself instead of $E$, since $E$ is defined as the specific application of $C$  ($L$ since we are talking about square error)

[^3]: and the product of the learning rate and gradient, multiplied by $-1$ guarantees that $w_{ij}$ changes in a way that always decreases $E$
