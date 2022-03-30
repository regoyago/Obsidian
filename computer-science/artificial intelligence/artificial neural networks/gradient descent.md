in mathematics gradient descent is a first order iterative optimisation [[algorithm]] for finding a [[extrema]] of a [[differentiable function]]
 
the idea is to take repeated steps in the opposite direction of the gradient of the function at a current point

gradient descent is based on the observation that:
if the multi variable function $F(x)$ is a defined and [[differentiable function]] in a neighbourhood of a point $a$, then $F(x)$ decreases fastest if one goes from $a$ in the direction of the negative gradient of $F$ at $a, -\nabla a$ , it follows that, if  
$a_{n+1} = a_n - \gamma \nabla F (a_n)$ 
for a small enough step size $\gamma \in \mathbb{R}_+$ then $F(a_n)\geq F(a_{n+1})$

with this observation in mind, one starts with a guess $x_0$ for a local minimum of $F$  and considers the sequence $x_{n+1} = n_n - \gamma_n \nabla F(x_n), \ n\geq 0$


#artificial_neural_networks 