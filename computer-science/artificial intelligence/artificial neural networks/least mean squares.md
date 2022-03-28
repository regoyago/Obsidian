least mean squares [[algorithm]]s are a class of [[adaptive filter]]s used to mimic a desired filter by finding the filter coefficients that relate to producing the least mean square of the error signal (difference between the desired and the actual signal)

it is a [[stochastic gradient descent]] method in that the filter is only adapted based on the error at the current time

definition of symbols:
- $n$ : the number of the current input sample
- $p$: the number of filter taps
- $\{\dot\ \}^H$: [[conjugate transpose matrix]]
- $x(n) = [x(n),x(n-1),\ldots x(n-p+1)]^T$
- $h(n) = [h_0(n), h_1(n),\ldots ,h_{p-1}(n)]^T$
- $y(n) = h^H(n) \dot \ x(n)$
- $d(n)= y(n)+ v(n)$
- $ĥ(n)$ estimated filter; interpret as the estimation of the filter coefficients after $n$ samples
- $e(n) = d(n) - ŷ(n) = d(n) -ĥ^H(n)\dot \ x(n)$

idea:
the basic idea is to approach the optimum filter weights $(R^-1 P)$, by updating the filter weights in a manner to converge to the optimum filter weight
this is based on the [[gradient descent]] algorithm
it starts by assuming small wights and, a each step, by finding the gradient of the mean square error, the weights are updated:

if the MSE-gradient is positive, the  error would keep increasing positively if the same weight is used for further iterations, which means we need to reduce the weights
otherwise, we need to increase the weights
the weight update [[mathematical equation]] is
$$W_{n+1} = W_n - \eta \nabla\epsilon[n]$$
where $\epsilon$ represents the mean-square error and $\eta$ is a convergence coefficient
the negative sign shows that we go down the slope of the error, $\epsilon$ to find the filter weights, $W_i$, which minimise the error

the mean square-error as a function of filter weights is a quadratic function which means it has only one extreme, that minimises the mean-square error, which is the optimal weight

#artificial_neural_networks 