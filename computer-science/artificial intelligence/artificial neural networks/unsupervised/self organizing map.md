 in [[artificial intelligence]], a self organizing map is ann [[unsupervised machine learning]] technique used to produce a low dimensional representation of a higher dimensional data set while preserving the topological structure of the data

that is, a type of [[artificial neural network]] trained using [[competitive learning]] rather than error correction methods

as most artificial neural networks, self organizing maps operate in two modes: training and mapping 

### learning algorithm
the weights of the neurons are initialized either to small random values 
the network must be fed a large number of example vectors that represent, as closely as possible the kind of veectors expected during mapping
each example can be administered several times as iterations
the training utilizes [[competitive learning]]
when a training  example is fed to the network, its [[euclidean distance]] to all weiight vectors is computed
the neuron whose weight vector is most similar to the input is called the best matching unit (BMU)
the weights of the BMU andd neurons close to it in the SOM grid are adjusted towards the input vector
the magnitude of the change decreases with time and woth the grid-distance from the BMU
the update formula for a neuron $v$, with weight vector $W_v(s)$ is:
$$W_v(s+1)= W_v(s)+\theta(u,v,s)\alpha(s)(D(t)-W_v(s))$$
