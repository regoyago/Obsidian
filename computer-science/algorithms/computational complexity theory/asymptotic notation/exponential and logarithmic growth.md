given $f(x)$, a [[monotonic function]], strictly increasing  
  
if there exists [[real number]]s $c>0$, $a>1$  
$$(f(n))^c=O(a^{f(n)})$$  
  
any [[exponential function]] with the base greater than one always grows faster than any [[polynomial function]]  
thus making exponential function the fastest growing  
  
moreover, from the previous theorem, if we apply it to the logarithm:  
  
$$(log_an)^c=O(a^{log_an})=O(n) \rightarrow (logn)^k=O(n) \ \ \ \forall k \text{ constant}$$  
that means that the linear function will eventually surpass the [[logarithmic function]]  
thus making logarithmic functions the slowest growing functions  
  
#algorithms  
#asymptotic_notation