the fundamental theorem of calculus is a theorem that links the concept of [[derivative]] with the concept of [[integral]]

I:
the first part of the theorem, often referred to as the first fundamental theorem of calculus, states that one of the [[indefinite integral - antiderivative]], say $F$, of some [[mathematical function]] $f$ may be contained as the  [[integral]] of $f$  with a variable bound of integration, this implies the existence of antiderivatives for [[continuous function]]s:

let $f$ be a [[continuous function]] over the [[real number]]s defined over a closed [[interval]] $[a,b]$, let $F$ be  the [[mathematical function]] defined $\forall x\in [a,b]$

$$F(x)=\int_a^x f(t)d(t)$$
then $F$ is uniformly [[continuous]] on $[a,b]$ and a [[differentiable function]] on the open interval $(a,b)$ and
$$F'(x)=f(x) \forall x\in (a,b)$$

corollary:
$$\int _a^b f(t)dt=F(b)-F(a)$$


II [[barrow's rule]]:
conversely, the second part of the theorem, often called the second fundamental theorem of calculus, states that the integral of a function $f$ over some [[interval]] can be computed by using any one, say $F$, of its infinitely many antiderivatives
this part of the theorem has key practical applications, because explicitly finding the antiderivative of a function by [[symbolic integration]] avoids [[numerical integration]] to compute [[integrals]]

let $f$ be a [[continuous function]] over the [[real number]]s defined over a closed [[interval]] $[a,b]$, let $F$ be an [[indefinite integral - antiderivative]] of $f$ in  $(a,b)$
$F'(x)=f(x)$
if $f$ is , by [[riemann integrable function]] on $[a,b]$, then:

$$\int_a^bf(x)dx = F(b)-F(a)$$

this part is stronger that the first corollary because it does not assume that $f$ is a [[continuous function]]

when an [[indefinite integral - antiderivative]] $F$ exists, there are infinitely many antiderivatives for $f$, obtained by adding an arbitrary constant to $F$
also, by the first part of the theorem, antiderivatives of $f$ always exist when $f$ is continuous


#integrals 