in the mathematical field of numerical analysis, a newton polynomial is an [[interpolation polynomial]] for a given [[set]] of data points

formally:
given a set of $k+1$ data points:$$(x_0,y_0),\ldots,(x_j,y_j),\ldots,(x_k,y_k)$$where no two $x_j$ are the same, the newton polynomial is a [[linear combination]] of newton basis polynomials[^1]
$$N(x):=\sum^k_{j=0}a_jn_j(x)$$
the coefficients are defined as $a_j:=[y_0,\ldots,y_j]$, where  $[y_0,\ldots,y_j]$ is the notation for [[divided differences]]

thus the newton polynomial can be written as:

$$N(x)=[y_0]+[y_0,y_1](x-x_0)+\ldots+[y_0,\ldots,y_k](x-x_0)(x-x_1)\ldots(x-x_{k-1})$$



[^1]: the newton basis polynomial would be defined as$$n_j(x):=\prod^{j-1}_{i=0}(x-x_i)$$ for $j>0$ and $n_0(x) \equiv 1$ 

#approximation_method