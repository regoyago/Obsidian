in [[set theory]], the intersection (denoted by $\cap$) of a collection of [[set]] is the set containing all elements 

it is one of the fundamental operations through which sets can be combined and related to each other

the intersection of two sets $A$ and $B$ is the set of elements which are in both sets:
$A\cap B = \{x:x\in A\ and\  x\in B\}$

the binary intersection has its following properties [^1]

- it is an [[associative]] operation; that is, for any sets $A$,$B$, $C$:
$A\cap (B\cap C)\ =\ (A \cap B)\cap C$ 
thus the parenthesis may be omitted without ambiguity

- it  is [[commutative]], so the sets can be written in any other

- the intersection with the [[empty set]] always results in the empty set

- the intersection operation is [[idempotent]]

- intersection has [[distributive property]] over [[union]] that is, for any sets $A$, $B$ and $C$, one has:
$A\cap (B\cup C) = (A\cap B)\cup (A\cap B)$
$A\cup (B\cap C) = (A\cup B)\cap (A\cup B)$


the most general notion is the intersection of an arbitrary collection of sets

if $M$ is a set or a class whose elements are sets, then $x$ is an element of the intersection $M$ if and only if for every element $A$ of $M$ such that $x$ is an element of $A$:
$$( x\in \bigcap_{A\in M} A ) \iff \forall A \in M, x\in A$$

[^1]: all of these properties are analogous to those of a [[logical conjunction]] 

#set_theory