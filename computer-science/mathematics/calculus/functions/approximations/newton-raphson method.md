in numerical analysis, also known as newton's method is a root-finding algorithm which produces successively better approximation of the roots of a [[mathematical function]] over the [[real number]]s  
  
the idea is to start with an initial guess which is reasonably close to the true root, then to approximate the function by its [[tangent line]], and finally to compute the x-intercept of the tangent line, this intercept will typically be a better approximation to the original function's root than the first guess, and the method can be iterated  
  
more formally, suppose $f:(a,b)\to \mathbb{R}$ a [[differentiable function]] defined on the interval $(a,b)$, with values in the [[real number]]s $R$, and a current approximation $x_n$ of the root  
then we can derive the formula for a better approximation $x_{n+1}$ by referring to the diagram on the right, the equation of the tangent line to the curve $y=f(x)$ at $x=x_n$ is [^1] :  
$y=f'(x_n)(x-x_n)+f(x_n)$  
where $f^(x_n)$ denotes the [[derivative]] of the function  
the x-intercept $(y=0)$ is taken as the next approximation $x_{n+1}$, to the root, so that the equation of the tangent line is satisfied when $(x,y)=(x_{n+1},0)$:  
$$0=f'(x_n)(x_{n+1})(x_{n+1}-x_n)+f(x_n)$$  
solving for $x_{n+1}$ gives:  
$$x_{n+1}=x_n-\frac{f(x_n)}{f'(x_n)}$$  
  
[^1]: by using the point-slope formula  
  
#approximation_method