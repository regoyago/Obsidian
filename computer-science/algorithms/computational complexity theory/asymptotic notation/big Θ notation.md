let $f$ and $g$ be [[mathematical function]]s, defined over the [[real number]]s, generally positive [[integer number]]s  
let both functions be defined on some unbounded [[subset]] of the positive [[real number]]s, and $g(x)$ be strictly positive for all large enough values of $x$  
one writes:  
$$f(x)=\Theta(g(x)) \ \ \ \ \ \ x\to \infty$$  
  
if the [[absolute value]] of $f(x)$ is at most a positive constant multiple of $g(x)$ for all sufficiently large values of $x$, that is $f(x)=\Theta(g(x))$ if there exists a positive real number $M$ and a real number $x_0$ such that $|f(x)|= M\ g(x) \ \ \ \ \forall x\geq x_0$  
  
that is to say, big $\Theta$ notation implies both a lower and an upper bound (exact bound) on the [[mathematical function]] representing the [[algorithm]], hence, big $\Theta$ notation is the intersection between [[big O notation]] and [[big Ω notation]]  
  
#algorithms  
#asymptotic_notation