in mathematics, the composition of relations is the forming of new [[binary relation]]s $R;S$ from two given relations $R$ and $S$

[[computer-science/mathematics/discrete mathematics/relations/functions/function composition]] is an special case of relation composition

formal definition:
if $R\subseteq X\times Y$ and $S\subseteq Y\times Z$ are two binary relations, then their composition $R;S$ is the relation

$$R;S =\{(x,z)\in X\times Z|\exists y\in Y : (x,y)\in R \wedge (t,z) \in S\}$$

in other words, $R;S \subseteq X\times Z$ is defined by the rule that says $(x,z)\in R;S$ if and only if there is an element $y\in Y$ such that $x\ R\ y \ S \ z$

#relations 