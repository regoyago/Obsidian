an artificial neuron is a [[mathematical function]] conceived as a [[model]] of biological neurons, and are defined as the elementary elements in a [[artificial neural network]]

this artificial neuron receives one or more inputs and sums them to produce an output 

usually each input is separately weighted[^1], and the sum is passed through a non-linear function known as [[activation function]][^2]

![[Pasted image 20220328162301.png]]

formally: 
for a given artificial neuron, $k$, let there be $m+1$ inputs with signals $x_o$ through $x_m$ and weights $w_{k0}$ through $w_{km}$
usually the $x_0$ input is assigned the value $+1$ which makes it a _bias_ input with $w_{k0} = b_k$
this leaves only $m$ actual inputs to the neuron: form $x_1$ to $x_m$

the output of the $k$th neuron is:$$y_k = \varphi\Big(\sum^m_{j=0} w_{kj}\ x_j\Big)$$
where $\varphi$ is the  [[activation function]]


the output is analogous to the axon of a biological neuron, and its value propagates to the input of the next layer, or exists the system, probably as a part of an output [[vector]][^2]

[^1]: note that the behaviour of an artificial neuron, then is similar to a [[linear regression]]
[^2]: this  separates the behaviour of a linear regression and is needed in order for several neurons to be connected in a [[artificial neural network]]
[^3]: it is important to note that a neuron has no learning process as such: its transfer function wights are calculated and threshold value predetermined

#artificial_neural_networks