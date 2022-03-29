in mathematics, divided differences is an [[algorithm]], historically used for computing tables of logarithmic and [[trigonometric function]]s

this method can be used to calculate the coefficients in the [[interpolation polynomial]] in the [[newton polynomial]] form

formally:
given $k+1$ data points
$(x_0,y_0),\ldots,(x_k,y_k)$

- the forward divided differences are defined as:
$$[y_v]:=y_v,\ \ \ \ v\in\{0,\ldots,k\}$$$$[y_v,\ldots,y_{v-j}]:=\frac{[y_{v+1},\ldots,y_{v+j}]-[y_{v},\ldots,y_{v+j-1}]}{x_{v+j}-x_v},\ \ \ v\in\{0,\ldots,k-j\},j\in\{1,\ldots k\}$$
#approximation_method