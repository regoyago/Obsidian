given $A=\{a_1,a_2,\ldots , a_n\}$, a finite [[set]] of $n$ elements and $r$, a [[natural number]] such that $r\leq n$
we define a [[variation]] with repetition of order $r$ of $n$ elements from $A$ as a selection or ordered list of $r$, not necessarily, different elements from the set $A$

we define a variation with repetition formally as:
$$VR(n,r)=n^r$$

we can prove this definition if we think about it as an application of the [[rule of product]]:
for the first element one of $n$ products is selected
for the second, one of $n$ again, since we are able to select any of the whole set
...
up until $n^r$

two variations with repetitions are different if the number of times that an element $n\in A$ appears is different or if it appears in a different position

generally, a couple of [[variation]]s with or without repetition, from a set $A$ of order $r$ are different if in any of the $r$ selections or positions, the correspondent elements of $A$ are different


we can define a variation of order $r$ from the elements in $A$ as a [[mathematical function]] (not necessarily injective, as with variations with repetitions) from $\{1,2,\ldots,r\}$ of $A$, being $f(1)$ the first element of the selection, $f(2)$ the second...

overall, the number of [[mathematical function]]s from a [`[set]`] of cardinal $r$ to a [[set]] of cardinal $n$, given $r\leq n$ is $$VR(n,r)=n^r$$
#combinatorics