a common basic [[predicate]] is the equality ($=$), which verifies the following axioms:
$$\forall x \ (x=x)$$$$\forall x \ \forall y \ ((x=y)\wedge P(x)) \ \rightarrow P(y))$$

moreover, when working with natural numbers, there exists a specific demonstration rule known as induction principle: 
{$P(1), \forall x(P(x)\rightarrow P(x+1))$} $\models \forall x \ P(x)$


we can use this method to prove that, from the universe $\mathbb{N}$, $\forall n \ P(n)$ is a true proposition:
- base case: $P(k_i)$, being generally, $i=1$
- inductive step: $\forall k \ (P(k)\models P(k+1))$

if both are true, then we conclude that $\forall n \ P(n)$ is a true proposition

so, if $P(1)$ is true and, $P$ is transmitted from a natural number $k$ to $k+1$, then all natural numbers will satisfy the property $P$

this property is usually compared to the fall of dominoes in a row

there is an equivalent principle [[strong induction]]

#mathematical_logic 
#induction