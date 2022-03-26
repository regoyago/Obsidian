in mathematics, a continuous [[mathematical function]] is a function that does not have any abrupt changes in value, known as [[discontinuities]]
more precisely, a  function is continuous if arbitrarily small changes in its output can be assured by restricting to sufficiently small changes in its input

a function $f$ with variable $x$ is said to be continuous at a certain point $c$ on the real line, if the [[limit]] of $f(x)$, as $x$ approaches $c$, is equal to the value $f(c)$; 
that is to say:
$$\lim_{x\to c} f(x) = f(c)$$ 

it is worth noting that in order for the [[limit]] when $x$ tends to $c$ to exist, the [[one-sided limit]]s must exist and be equal, hence, extending the aforementioned definition to:

$$(\exists \lim_{x\to c^-} f(x) = \exists \lim_{x\to c^+} f(x)) \iff \exists \lim_{x\to c} f(x)$$

$$\lim_{x\to c} f(x) = f(c)$$


regarding the continuity of functions, the following properties are worth-noting:
- if $f,g:(a,b)\rightarrow \rightarrow \mathbb{R}$ are continuous functions at $c \in (a,b)$
	- $\lambda f$ is continuous at $c, \ \forall \lambda \in \mathbb{R}$
	- $(f\pm g)$ and $f \times g$ are continuous at $c$
	- if $g(c)\neq 0$, then $\frac{f}{g}$ is continuous at $c$

- limit operators is [[conmutative]] for continuous functions:
$$\lim_{x\to c} g(f(x))=g(\lim_{x\to c}f(x))=g(l)$$
- if $f$ is continuous at $c$ and $g$ is continuous at $f(c)$, then, the function $f\circ g$ is continuous at $c$


a function is continuous (as a whole) if all its points are continuous

a [[mathematical function]] will be continuous at a certain [[interval]] if it is continuous at all the points inside the interval:
given $f:[a,b]\in \mathbb{R}\to \mathbb{R}$, we say that $f$ is continuous on $[a,b]$ if:
- $f$ is continuous in $(a,b)$
- $f$ is right-continuous or continuous at $a$ from the right: $\lim_{x\to a^+} f(x)=f(a)$
- $f$ is left-continuous or continuous at $b$ from the left: $\lim_{x\to b^-} f(x)=f(b)$