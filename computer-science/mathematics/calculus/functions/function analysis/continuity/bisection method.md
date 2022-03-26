in mathematics, the bisection method is a root-finding method that applies to [[continuous function]]s for which one knows two values of different sign (and thus, applying [[bolzano's theorem]], it is true that there is at least one solution)

the method consists of repeatedly bisecting the [[interval]] defined by these values and then selecting the sub-interval in which the [[mathematical function]] changes sign , and therefore must contain a root:

- initialize $[a_1,b_1]= [a,b]$
- for $k=1,2,\ldots$
	- compute $x_k=\frac{a_k+b_k}{2}$
	- if $f(a_k)f(b_k)<0$ update $[a_{k+1},b_{k+1}]=[a_k,x_k]$
	- else $[a_{k+1},b_{k+1}]=[x_k,a_k]$
this process is repeated until $x_k$ is a good approximation of the root $\alpha$
note that $|x_k-\alpha |\leq \frac{b-a}{2^k}$