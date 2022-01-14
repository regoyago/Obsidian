given $A=\{a_1,a_2,\ldots , a_n\}$, a finite [[set]] of $n$ elements and $r$, a natural number such that $r\leq n$
we define a variation (ordinary, without repetition) of order $r$ of $n$ elements from $A$ as a selection or ordered list of $r$ different elements from the set  $A$

for the mathematical definition,  we need the definition of [[factorial]]:

$$V(n,r)=n*(n-1)*(n-2)\ldots *(n-(r-2))*(n-(r-1)) =\frac {n!}{(n-r)}$$

we can prove this definition if we think about it as an application of the [[rule of product]]:
for the first element one of $n$ products is selected
for the second, one of $n-1$
...
up until $n-r$

generally, a couple of [[variation]]s with or without repetition, from a set $A$ of order $r$ are different if in any of the $r$ selections or positions, the correspondent elements of $A$ are different


we can define a variation of order $r$ from the elements in $A$ as an [[injection]] from $\{1,2,\ldots,r\}$ of $A$, being $f(1)$ the first element of the selection, $f(2)$ the second...

overall, the number of [[injection]]] from a [[set]] of cardinal $r$ to a set of cardinal $n$, given $r\leq n$ is $n*(n-1)*(n-2)\ldots *(n-(r-2))*(n-(r-1)) =\frac {n!}{(n-r)""}=V(n,r)$

#combinatorics