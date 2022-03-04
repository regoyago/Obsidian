given $A=\{a_1,a_2,\ldots , a_n\}$, a finite [[set]] of $n$ elements and $r$, a natural number such that $r\leq n$
we define a [[combination]] (simple or without repetition) of order $r$ of $n$ elements from $A$ as a subset (not ordered selection) with $r$ elements of $A$

two combinations will be different if they differ on any element

we define mathematically the concept of combination as follows:
$$C(n,r)=\frac{n!}{r!(n-r)!}$$

this definition can be demonstrated as follows:
from each of the $C(n,r)$ possible combinations, there exist $P(r)=r!$ different [[variation]]s; the possible ways that $r$ elements can be ordered
by the [[rule of product]]:
$$C(n,r)*r!=V(n,r)=\frac{n!}{(n-r)!}$$

the number by which we define the combination is called [[binomial coefficient]]

$$\binom{n}{r}=\frac{n!}{r!(n-r)!}$$

from this definition, for a given $n$ and $r$, such that $0\leq r \leq n$, we verify that:
$$\binom{n}{r}=\binom{n}{n-r}$$
#combinatorics