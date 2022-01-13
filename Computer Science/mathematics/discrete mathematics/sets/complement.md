in [[set theory]], the complement of a [[set]] $A$, often denoted by $A'$ or $A^C$ are the elements that are not in $A$

when all sets under consideration are considered to be [[subset]]s of a given set $U$, the absolute complement of $A$ is the set of elements in $U$that are not in $A$, this kind of complement is defined as an absolute complement[^1]

$$A^C = U\backslash A$$
$$A^C =  \{x\in U : x\notin A\}$$

let $A$ and $B$ be two sets in a universe $U$, the following identities capture important properties of absolute complements:
- [[de morgan's laws]]
	- $(A\cup B)^C = A^C \cap B^C$
	-  $(A\cap B)^C = A^C \cup B^C$
-  complement laws[^1]:
	-  $A\cup A^C = U$
	-  $A\cap A^C = \emptyset$
	-  $\emptyset^C = U$
	-  $U^C = \emptyset$
	-  if $A \subseteq B$, then $B^C\subseteq A^C$
-  double complement law:
	-  ${A^C}^C=A$
-  relationships between absolute and [[relative complement]]s
	-  $A \backslash B = A\cap B^C$
	-  $(A\backslash B)^C = A^C \cup B = A^C\cup (B\cap A)$
- relationships with difference
	- $A^C\backslash B^C = B\backslash A$

#set_theory

[^1]: this first two show that if $A$ is a non-empty , proper [[subset]] of $U$ then $\{A,A^C\}$ is a [[partition]] of $U$