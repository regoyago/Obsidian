given $x$ and $y$ two variables and $n$, a natural number:
$$(x+y)^n=\sum_{k=0}^{n}\binom{n}{k}x^k*y^{n-k}=\sum_{k=0}^{n}\binom{n}{k}x^{n-k}*y^{k}$$


which can be proven:
$$(x+y)^n=(x+y)*\underbrace{\ldots}_{n}*(x+y)$$ for each value of $k$, $0\leq k\leq n$, the coefficient of $x^k*y^{n-k}$ is the same as the number of ways in which you can select the variable $x$ in $k$ of the $n$ factors (selecting the variable $y$ in the $n-k$ factors left), with irrelevant order and without repeating factors
this is, it can be generalized, using a [[combination]] in
$C(n,k)-\binom{n}{k}$ ways, hence:

$$(x+y)^{n}=\sum_{k=0}^{n}\binom{n}{k}x^k*y^{n-k}$$
the second equality can be obtained from $(x+y)^n=(y+x)^n$


corollary:
$$\sum_{k=0}^{n}\binom{n}{k}=2^n$$
$$\sum_{k=0}^{n}(-1)^k\binom{n}{k}=0$$
proof: we take the theorem with $x=y=1$ on the first equality and $x=1$,$y=-1$ on the second
remainders:
- $2^n$ is the number of [[subset]]s of a [[set]] of cardinal $n$
- $\binom{n}{k}$ is the number of subsets of cardinal $k$, for $k=0,1,2,\ldots ,n$

#combinatorics 