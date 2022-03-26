from the definition of [[derivative at a point]], we can get a [[mathematical function]] which represents the change of slope on a whole [[differentiable function]] 

$$\frac{d}{dx}x^n=nx^{n-1}$$

$$\frac{d}{dx}lnx=\frac{1}{x}$$

$$\frac{d}{dx}log_a x= \frac{1}{x}log_a e$$

$$\frac{d}{dx}e^x=e^x$$

$$\frac{d}{dx} a^x=a^xln a$$

$$\frac{d}{dx} sin(x)=cos(x)$$

$$\frac{d}{dx} cos(x)=-sin(x)$$

$$\frac{d}{dx}tan(x)=\frac{1}{cos^2(x)}$$

$$\frac{d}{dx} arcsin(x)=\frac{1}{\sqrt{1-x^2}}$$

$$\frac{d}{dx} arccos(x)=\frac{-1}{\sqrt{1-x^2}}$$

$$\frac{d}{dx} arctan(x)=\frac{1}{{1+x^2}}$$


given $f, g :(a,b)\to \mathbb{R}$, two [[differentiable function]]s at a point $x_0 \in (a,b)$ and $\lambda \in \mathbb{R}$, then:
- $(\lambda f)'(x_0) = \lambda f'(x_0)$ 
- $(f\pm g)'(x_0) = f'(x_0)+g'(x_0)$
- $(fg)'(x_0)=f'(x_0)g(x_0)+f(x_0)g'(x_0)$[^1]
- ${\left( \frac{f}{g} \right)}^{'}(x_0)=\frac{f'(x_0)g(x_0)-f(x_0)g'(x_0)}{g(x_0)^2}$, if $g(x_0)\neq 0$
- [[chain rule]]

higher order derivatives can be defined as such:
let $f:(a,b)\rightarrow \mathbb{R}$  a [[differentiable function]] on $(a,b)$, the following derivative function is defined:
$$f'(a,b)\to \mathbb{R}$$
$$x\mapsto f'(x)$$

- given $x_0\in(a_b)$ we define [^2] :

$$f''(x_0)=(f')'(x_0)= \lim_{h\to 0}\frac{f'(x_0+h)-f'(x_0)}{h}$$
if this [[limit]] exists and is finite, it is said that  $f$ is a two times [[differentiable function]] at $x_0$

- in general, once  we have $f^{(n)}:(a,b)\to \mathbb{R}$, we define:
$$f^{(n+1)}(x_0)={(f^{(n)})}'(x_0)$$

#derivatives

[^1]:[[leibniz's product rule]]
[^2]: by using the definition of [[derivative at a point]]