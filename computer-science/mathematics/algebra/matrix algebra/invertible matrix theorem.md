let $A$ be a [[square matrix]] over a [[mathematical field]] $\mathbb{K}$, the following statements are equivalent:
- there is a $n\times n$ [[matrix]] $B$ such that $AB=I_n=BA$
- the matrix $A$ has a left inverse matrix ($\exists B \mid BA = I$) or a right inverse ($\exists C \mid AC = I$), in case both exists, $A$ is [[invertible matrix]] and $A^{-1} = B = C$
- $A$ is an invertible matrix
- $A$ is row-[[equivalent matrix]] to the [[identity matrix]] $I_n$
- $A$ is column-[[equivalent matrix]] to the identity matrix $I_n$
- $A$ has $n$ pivot positions
- $A$ has a full [[rank]], $n$[^1]
- the [[kernel]] of $A$ is trivial (contains only the  null vector, $ker(A) = \{0\}$) 
- the columns of $A$ have [[linear independence]]
- the columns of $A$ [[span]] $\mathbb{K}$
- the [[column space]] of $A$ forms a [[basis]] of $\mathbb{K}^n$
- the [[linear transformation]] mapping $x$ to $Ax$ is a [[bijection]] $\mathbb{K}^n\rightarrow \mathbb{K}^n$
- the [[determinant]] of $A$ is different from $0$ [^2]
- the number $0$ is not an [[eigenvalue]] of $A$
- the [[transpose matrix]] $A^T$ is an invertible matrix [^3]
- $A$ can be expressed as a finite product of [[elementary matrix]]

[^1]:based on this, the equation $Ax = 0$ has only the trivial solution $x=0$, and the equation $Ax=b$ has exactly one solution for each $b\in \mathbb{K}^n$ 
[^2]: in general, a [[square matrix]] over a [[commutative ring]] is invertible if and only if its determinant is a unit in that ring
[^3]: hence, rows of $A$ have [[linear independence]], span $\mathbb{K}^n$ and form a basis of $\mathbb{K}$

#matrix 