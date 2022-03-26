big O notation is a mathematical notation that describes the limiting behaviour of a [[mathematical function]] when the variable tends towards a particular value or infinity  
  
specifically in computer science, big O notation is used to classify [[algorithm]]s according to how their runtime or space requirements grow as the input size grows  
  
big O notation characterises functions according to their growth rates: different functions with the same growth rate may be represented using the same O notation  
the letter O is used because the growth rate of a function is also referred to as the order of the function  
a description of a function in terms of big O notation usually only provides an upper bound of the growth rate of the function  
  
  
formally:  
  
let $f$ and $g$ be [[mathematical function]]s, defined over the [[real number]]s, generally $f(x):\mathbb{Z}\to\mathbb{R}$ positive [[integer number]]s  
let both functions be defined on some unbounded [[subset]] of the positive [[real number]]s, and $g(x)$ be strictly positive for all large enough values of $x$  
one writes:  
$$f(x)=O(g(x)) \ \ \ \ \ \ x\to \infty$$  
  
if the [[absolute value]] of $f(x)$ is at most a positive constant multiple of $g(x)$ for all sufficiently large values of $x$, that is $f(x)=O(g(x))$ if there exists a positive real number $c$ and a real number $x_0$[^2] such that $|f(x)|\leq c\ g(x) \ \ \ \ \forall x\geq x_0$  
  
in many contexts, the assumption that we are interested in the growth rate as the variable $x$ goes to infinity is left unstated, and one writes more simply that:  
$$f(x)=O(g(x))$$  
  
the notation can also be used to describe the behaviour of $f$ near some real number $a$, often $a=0$:  
$$f(c)=O(g(x))\ \ \ \ \ x\to a$$  
  
if there exist positive numbers $\delta$ and $c$ such that $\forall x$ with $0<|x-a|<\delta$  
$$|f(x)|\leq c g(x)$$  
  
as $g(x)$ is chosen to be non-zero for values of $x$ sufficiently close to $a$, both of these definitions can be unified using the [[limit]]:  
  
$$f(x)=O(g(x))\ \ \ \ \ x\to a$$
if  $$\lim_{x\to a}\frac{|f(x)|}{g(x)}$$  
  
  
- product property:  
$$f_1=O(g_1)\text{ and }f_2=O(g_2) \implies f_1f_2=O(g_1g_2)$$
$$f.O(g)=O(fg)$$    
- sum rule:  
$$f_1=O(g_1)\text{ and }f_2=O(g_2) \implies f_1+f_2=O\ (max(g_1g_2))$$  
  
- multiplication by a constant:  
let $k$ be a nonzero constant, then $O(|k|.g)=O(g)$. In other words, if $f=O(g)$, then $k.f=O(g)$  
  
  
order of common functions:  
- $O(1)$: constant  
- $O(log\ log\ n)$: double [[logarithmic function]]  
- $O(log\ n)$: [[logarithmic function]][^1]  
- $O((log\ n)^c)$: polylogarithmic  
- $O(n^c)$: fractional power  
- $O(n)$: linear  
- $O(n log* n)$:n log-star n  
- $O(n log n)= O(logn!)$: linearithmic  
- $O(n^2)$: quadratic  
- $O(n^c)$: algebraic  
- $O(c^n)$: exponential  
- $O(n!)$: factorial  
  
  
other related asymptotic notations: [[little o notation]], [[big Ω notation]]  
  
  
[^2]: this number is defined as the [[threshold]]  
[^1]: even though normally logarithms on computations will appear as $log_2$, the base in the end does not matter, since we can change the basis of a [[logarithmic function]] by multiplying by a constant, rendered useless by the big O notation  
  
#algorithms  
#asymptotic_notation