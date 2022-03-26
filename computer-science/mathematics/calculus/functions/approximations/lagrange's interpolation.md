for a given [[set]] of points $(x_j,y_j)$ with no two $x_j$ values equal, the lagrange polynomial is the polynomial of lowest degree that assumes at each value $x_j$ the corresponding value $y_j$, so that the [[mathematical function]]s coincide at each point  
  
lagrange interpolation is susceptible to runge's phenomenon of large oscillation , as changing the points $x_j$ requires recalculating the entire interpolant, it is often easier to use [[newton polynomial]]s instead  
  
  
given a [[set]] of $k+1$ data points $(x_0,y_0),\ldots , (x_j,y_j),\ldots , (x_k,y_k)$ where no $x_j$ are the same, the interpolation polynomial in the lagrange form is a [[linear combination]]  
$$L(x):=\sum_{j=0}^ky_jl_j(x)$$  
of lagrange basis polynomials  
$$l_j(x):=\prod_{0\leq m\leq k \backslash m\neq k} \frac{x-x_m}{x_j-x_m}=\frac{x-x_0}{x_j-x_0}\ldots \frac{x-x_{j-1}}{x_j-x_{j-1}} \frac{x-x_{j+1}}{x_j-x_{j+1}} \ldots \frac{x-x_{k}}{x_j-x_{k}}$$  
  
where $0 \leq j\leq k$  
  
note how, given the initial assumption that no $x_j$ are the same, then (when $m\neq j$) $x_j-x_m\neq 0$, so this expression is always well defined  
  
the reason pairs $x_i=x_j$ with $y_i\neq y_j$ are not allowed is that no interpolation function $L$ such that $y_i=L(x_i)$ would exist; a function can only get one value for each argument $x_i$  
on the other hand, if also $y_i=y_j$, then those two points would actually be the same point  
  
for all $i\neq j, l_j(x)$ includes the term $(x-x_i)$ in the numerator, so the whole product will be zero at $x=x_i$:  
  
$$\forall (j\neq i): l_j(x_i)= \prod_{m\neq j}\frac{x_i-x_m}{x_j-x_m}=\frac{x_i-x_0}{x_j-x_0}\ldots \frac{x_i-x_{i}}{x_j-x_{i}} \ldots \frac{x_i-x_{k}}{x_j-x_{k}}=0$$  
  
on the other hand,  
  
$$l_j(x_j):=\prod_{m\neq j}\frac{x_j-x_m}{x_j-x_m}=1$$  
  
in other words, all basis polynomials are zero at $x=x_j$, except $l_j(x)$, for which it holds that $l_j(x_j)=1$, because i lacks the $(x-x_j)$ term  
it follows that $y_jl_j(x_j)=y_j$, so at each point $x_j$, $L(x_j)=y_j+0+0+\ldots +0 = y_j$, showing that $L$ interpolates the function exactly  
  
  
the lagrange interpolating polynomial for the nodes $x_0,x_1,\ldots , x_n$ and the values $\omega_0 , \omega_1 , \ldots \omega_n$ is  
$$p_n(x)=\omega _0 l_0(x)+\omega _1 l_1(x)+\ldots +\omega _n l_n(x)$$  
  
#approximation_method