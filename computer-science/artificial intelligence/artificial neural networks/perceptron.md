in the context of [[artificial neural network]]s, a perceptron is an [[artificial neuron]] using the [[heaviside]] mathematical function as the [[activation function]][^1]

formally, the perceptron is an algorithm for learning a binary classifier: a function that maps its input to $x$ (a real-valued [[vector]]) to an output value $f(x)$ (a single binary value)
$$f(x) =
\begin{cases}
    1 \text{ if } w \dot \ x + b > 0\\
    0 \text{ otherwise}
\end{cases}
$$
where  $w$ is a a vector of real valued weights $w \dot \ x$ is the [[dot product]] $\sum^m_{i=1}w_i\dot \ x_i$, where $m$ is the number of inputs to the perceptron, and $b$ the bias
the bias shifts the decision boundary away from the origin and does not depend on any input value

[^1]: as a linear classifier, the single layer perceptron is the simplest [[feedforward neural network]]  

#artificial_neural_networks 
