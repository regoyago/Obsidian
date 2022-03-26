in mathematics, the riemann integral was the first rigorous definition the [[integral]] of a [[mathematical function]] on in [[interval]]

the riemann integral is unsuitable form many theoretical purposes

let $f$ be a non-negative  [[mathematical function]] over the [[real number]]s  on the [[interval]] $[a,b]$ and let 

$$S=\{(x,y) : <\leq x\leq b, 0<y<f(x)\}$$
be the region of the plane under the graph of the [[mathematical function]] $f$ and above the interval  $[a,b]$ , we measure the [[area]] of $S$, we denote the area by :

$$\int^b_af(x)dx$$

the basic idea of the riemann integral is to use very simple approximations for the area of $D$

where $f$ can be both positive and negative, the definition of $S$ is modified so that the integral corresponds to the signed  area under the graph of $f$: that is: the area above the x-axis minus the area bellow it

properties:
let $f,g\in R[a,b]$, then:
- $f\pm g \in R[a,b]$ and $cf\in R[a,b] \ \ \ \ \forall c\in \mathbb{R}$, and they satisfy:
	-  $\int_a^b(f\pm g)(x)dx=\int_a^b f(x)dx \pm \int_a^b g(x)dx$
	-  $\int_a^b (cf)(x)dx= c\int_a^b f(x)dx$
	 
- $fg\in R[a,b]$

- if $a<c<b$, then $f\in R[a,c]$ and $f\in R[c,b]$ and:
	$\int_a^b f(x)dx=\int_a^c f(x)dx+\int_c^b f(x)dx$
-  if $f\leq g$ on $[a,b]$, then $\int_a^bf(x)dx \leq \int_a^b g(x)dx$
-  if $m\leq f(x)\leq M, \ \ \ \ \forall x\in [a,b]$
		$m(b-a)\leq \int_a^bf(x)dx\leq M(b-a)$
- $|f|\in R[a,b]$ and $\left| \int_a^bf(x)dx \right|\leq \int_a^b |f(x)|dx$ 

a riemann integral can be generalized as an  [[improper integral]] when the [[interval]] is $(-\infty , \infty)$

other formulas to calculate numerical integrals
- rectangle formula: $$\int_a^bf(x)dx\simeq (b-a)f(x_0), \ \ \ \ \ \ \ x_0\int [a,b]$$
- trapezoid rule: $$\int_a^b f(x)dx \simeq \frac{b-a}{2}(f(a)+f(b))$$
- simpson rule: $$\int_a^b f(x)dx \simeq \frac{b-a}{6}(f(a)+4f(\frac{a+b}{2})+f(b))$$

composite rules
- divide the integration interval in $n$ subintervals with the same length: $$x_i=a+ih \ \ \ \ (i=0,1,\ldots , n)\ \ \ \  \text{with} h= \frac{b-a}{n}$$
- the integral is approximated using a simple formula on each subinterval $$\int_a^b f(x)dx= \sum^{n-1}_{i=0}\int_{x_i}^{x_{i+1}} f(x)dx$$
	- composite midpoint rule: $$\int_a^b f(x)dx \simeq h \sum_{i=0}^{n-1}f(\frac{x_i+x_{i+1}}{2})$$
	- composite trapezoid rule: $$\int_a^bf(x)dx \simeq \frac{h}{2}(f(x_0)+2\sum_{i=1}^{n-1}f(x_i)+f(x_n))$$

#integrals 