in mathematics, specially [[order theory]] a poset, also known as a partially ordered set, its a [[set]] with a [[partial order]] on it
given a poset $(P,\preceq)$
- an element $a\in P$ is a [[maximal]][^1] element if there does not exist an element $x\in P$ such that $a\preceq x$ and $a\neq x$
- an element $b\in P$ is a [[minimal]][^2] element if there does not exist an element $x\in P$ such that $x\preceq b$ and $b\neq x$
- an element $M\in P$ is a maximum [^3]of $P$ if $x\preceq M$, for all $x\in P$ []
- an element $m\in P$ is a minimum[^4] of $P$ if $m\preceq x$, for all $x\in P$ 

given the same poset $(P,\preceq)$, and $Q$ a [[subset]] of $P$
- an element $s\in P$ is an upper bound of $Q$ in $P$  if $q\preceq s$ for any $q\in Q$
- an element $f\in P$ is a lower bound of $Q$ in $P$  if $f\preceq q$ for any $q\in Q$
- an element $S\in P$ is a [[supremum]][^5] of $Q$ in $P$ if $S$ is an upper bound of $Q$ in $P$ and if $S'$ is another upper bound of $Q$ in $P$, then $S\preceq S'$
- an element $I\in P$ is a [[infimum]][^6] of $Q$ in $P$ if $I$ is a lower bound of $Q$ in $P$ and if $I'$ is another lower bound of $Q$ in $P$, then $I'\preceq I$

[^1]:that is to say, there is not a single element strictly bigger than $a$
[^2]: that is to say, there is not a single element strictly smaller than $b$
[^3]: a maximum exists only if $P$ is finite and it has an unique maximal, or there exists the supremum of $Q$
[^4]: a minimum exists only if $P$ is finite and it has  an unique minimal, or there exists the infimum of $Q$
[^5]: a supremum, if it exists, it is unique
[^6]: an infimum, if exists, it is unique

#set_theory 
#order_theory
