given $A=\{a_1,a_2,\ldots , a_n\}$, a finite [[set]] of $n$ elements and $r$, a natural number
we define a [[combination]] with repetition of order $r$ of $n$ elements from $A$ as a non-ordered selection of $r$ elements, not necessarily different from $A$

two combinations with repetition of order $r$ are different if the number of times an element form the set $A$ appears differs

we define a mathematically a combination with repetition as:
$$CR(n,r)=C(n+r-1,r)=\binom{n+r-1}{r}=\binom{n+r-1}{n-1}$$

the proof of this definition is as follows:
each combination with repetition of order $r$ from the elements of $A$ corresponds to a solution of 
$$x_1+x_2+\ldots +x_n=r$$being $x_i$ the number of times we select the $i^{th}$ element 
hence, we are considering only solutions $(x_1,x_2,\ldots ,x_n)$with $x_i\in \mathbb{Z}, x_i\geq 0$, for each $i$
also, each non-negative solution $(x_1,x_2,\ldots ,x_n)$ of the latter equation, corresponds to a chain of $r$ 0 and $n-1$ | distributed as 
$$\overbrace{1\ldots 1}^{x_1}|\overbrace{1\ldots 1}^{x_2}||\overbrace{1\ldots 1}^{x_n}$$hence, if we want to obtain the number of ways of reordering $n-1$ | in $n+r-1$ positions, that number is:
$$\binom{n+r-1}{r}=\binom{n+r-1}{n-1}$$

#combinatorics