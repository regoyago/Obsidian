in linear algebra, an $n\times n$ [[square matrix]] $A$ is called invertible (also nonsingular or nondegenerate), if there exists an $n\times n$ square [[matrix]] $B$ such that
$$AB = BA = I_n$$
where $I_n$ denotes the $n \times n$ [[identity matrix]] and the multiplication used is ordinary [[matrix multiplication]]
if this is the case, then $B$ is uniquely determined by $A$ and is called the (multiplicative) inverse of $A$, $A^{-1}$

a square matrix that is not invertible is called singular or degenerate, if that is the case, the [[determinant]] will be $0$

non-square matrices do not have an inverse perse, bu may have a left or right inverse
- if $A$ is $n \times m$ and the [[rank]] of $A$ is equal to $n(n\leq m)$, then $A$ has a left inverse matrix $B$ such that $BA = I_n$
- if $A$ has rank $m(m\leq n)$, then it has a right inverse $B_{n\times m}$ such that $AB = I_m$

while the most common case is that of matrices over the [[real number]]s or [[complex number]]s, all these definitions can be given for matrices over any [[mathematical ring]]

the following properties hold for an invertible matrix $A$:
- $(A^{-1})^{-1} =  A$
- $(\lambda A)^-1 = \lambda^{-1}A^{-1}$ for nonzero scalar $\lambda$
- $(Ax)^+ = x^+A^{-1}$ has orthonormal columns
- $(A^T)^{-1}=(A^{-1})^T$
- for any invertible matrices $A\text{ and }B$, $(AB)^{-1} = B^{-1} A^{-1}$
- $det(A^{-1}) = (det A)^{-1}$

the following is also true:
let $A$ be an [[invertible matrix]] of size $n$, then 
	$$A^{-1}=\frac{1}{detA}\times adjA$$
where $adjA$ is the [[adjugate matrix]]  of $A$

#matrix 