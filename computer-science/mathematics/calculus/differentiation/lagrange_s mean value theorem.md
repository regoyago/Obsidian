in mathematics, the mean value theorem states, roughly, that for a given planar arc  between two endpoints, there is at least one point at which the [[tangent line]] to the arc is parallel to the [[secant line]] through its endpoints

is one of the most important results in real analysis

more precisely, the theorem states that if $f$ is a [[continuous function]] on the closed interval $[a,b]$ and a [[differentiable function]] on the open interval $(a,b)$, then there exists a point $c\in (a,b)$ such that the tangent at $c$ is parallel to the secant line through the endpoints $(a,f(a)), (b,f(b))$, that is:

$$f'(c)=\frac{f(b)-f(a)}{b-a}$$

the mean value theorem is a generalization of [[rolle's theorem]]which assumes $f(a)=f(b)$, so that the right-hand side above is $0$

the mean value theorem is still valid is a slightly more general setting:
one only needs to assume that $f:[a,b]\to \mathbb{R}$ is a  [[continuous function]], and that for every $x$ in $(a,b)$ the [[limit]]

$$\lim_{h\to 0}\frac{f(x+h)-f(x)}{h}$$

exists as a finite number or equals $\pm \infty$, if finite, that limit equals $f'(x)$


applications[^1] : let $f$ be a [[differentiable function]] on $(a,b)$
- if $f(x)\geq 0, \ \ \forall x \in (a,b), \ \ \ f$ is a [[monotonic function]] constantly increasing on the interval
-  if $f(x)\leq 0, \ \ \forall x \in (a,b), \ \ \ f$ is a [[monotonic function]] constantly decreasing on the interval
-   if $f(x)= 0, \ \ \forall x \in (a,b), \ \ \ f$ is constant on the interval
-    if $f(x)\neq 0, \ \ \forall x \in (a,b), \ \ \ f$ is a [[injective function]] on the interval

[^1]: related to the [[monotonic function]]s and [[extrema]]
#derivatives 