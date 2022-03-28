ADALINE (adaptive linear neuron or later adaptive linear element) is an early single layer [[artificial neural network]] and the name of the physical device that implemented this network

formally:
adaline is a single layer neural network with multiple nodes where each node accepts multiple inputs and generates one output, given the following variables as:
- $x$ the input vector
- $w$ the weigh factor
- $n$ the number of inputs
- $\theta$ some constant
- $y$ output of the model

then we find that the output is $y = \sum^n_{j=1}x_jw_j\theta$ 
if we further assume that $x_0 = 1$ , $w_0 = \theta$  then $y = \sum^n_{j=0}x_jw_j$

the learning algorithm can be formalised as follows: 
- $\eta$ is the [[learning rate]]
- $y$ is the output of the model
- $\omicron$ is the target (desired) output

then the weights are updated as follows: $w \leftarrow w + \eta(\omicron -y)x$  
the adaline converges to the [[least square error]]s which is $E = (\omicron - y)^2$
this update rule is in fact the [[stochastic gradient descent]] update for [[linear regression]]

#artificial_neural_networks 