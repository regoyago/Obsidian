a multilayer perceptron is a class of [[artificial neural network]]

it generally refers to the  network composed of multiple layers of [[perceptron]]s but can also be used generally as a synonym to [[artificial neural network]]

![[Pasted image 20220331163531.png|560]]

a multilayer perceptron consists of 3 fully connected[^1]  [[node layer]]s:
- input layer: formed of [[artificial neuron]]s that do not compute data, just store entries and forward them to the next layer
- hidden layer: [^2]
- output layer: they emit the output

##### [[activation function]] 

if a multilayer perception has a linear activation function,  [[linear algebra]] shows that any number of layers can be reduced to a two-layer input-output model
in multilayered perceptrons, some [[artificial neuron]]s use a nonlinear activation function that was developed to model the frequency of action potential, or firing of biological neurons

the two historically common activation functions are [[sigmoid]]s, described by
$$y(v_i) = tanh(v_i) \ \ \text{ and }\ \ y(v_i)=(1+e^{-v_i})^{-1}$$
in recent developments of [[deep learning]], the [[ReLU]] is more frequently used

  
##### learning

learning occurs in the perceptron by changing the connection weights after each piece of data is processed, based on the amount of error in the output compared to the expected result
this is an example of [[supervised learning]] and is carried out through [[backpropagation algorithm]], a generalisation of the [[least mean squares]]
in this specific example, the formalisation of this algorithm would be as follows:

##### [[backpropagation algorithm]]

hidden layer (h) - neuron j | output layer (o) - neuron k
------------- | -------------
error calculated from the output of $PE_j$ and the <br> backpropagated output error to that layer <br> $\delta^h_{pj}=f^h_j(neta^h_{pj}\sum_k\delta^\omicron_{pk}w^\omicron_{kj})$  |   error calculated from the output of $PE_j$ <br> and output error $\delta_{pk}$ <br> $\delta^\omicron_{pk} = \delta_{pk}f^0_k(neta^0_{pk})$
the variation of the weights is calculated <br> from $\delta^h_{pj}$ and the inputs to the neuron <br> $w^h_{ji}(t+1)=w^h_{ji}(t)+\mu\delta^h_{pj}i^{h-1}_i$ | the variation of the weights is calculated<br> from $\delta^o_{pk}$ and inputs to the neuron <br> $w^o_{kj}(t+1)=w^o_{kj}(t)+\mu\delta^o_{pk}i^{o-1}_{pj}$


 

#artificial_neural_networks  

[^1]: thus, the graph of the neural network would be a [[complete graph]]
[^2]: the exact working of these layers is not fully known yet, they are usually referred to as a blackbox