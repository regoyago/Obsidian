in mathematics, particularly in linear algebra, matrix multiplication is a binary operation that produces a [[matrix]] from two matrices

for matrix multiplication, the number of columns in the first matrix must be equal to the number of rows in the second matrix
the resulting matrix is called the matrix product

formally:
given the matrices $A,B$ $$A = \begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix} \ \ \ B =\begin{pmatrix}
b_{1,1} & b_{1,2} & \cdots & b_{1,n} \\
b_{2,1} & b_{2,2} & \cdots & b_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
b_{m,1} & b_{m,2} & \cdots & b_{m,n} 
\end{pmatrix}$$
the matrix product $C=AB$ is:
$$C =\begin{pmatrix}
c_{1,1} & c_{1,2} & \cdots & c_{1,n} \\
c_{2,1} & c_{2,2} & \cdots & c_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
c_{m,1} & c_{m,2} & \cdots & c_{m,n} 
\end{pmatrix}$$
such that $c_{ij} = a_{i1}b_{1j}+a_{i2}b_{2j}+\ldots+a_{in}b_{nj} = \sum^n_{k=1}a_{ik}b_{kj}$
that is, the entry $c_{ij}$ of the product is obtained by multiplying term-by-term the entries of the $i$th row of $A$ by the $j$th column of $B$, and summing these $n$ products
therefore $AB$ can also be written as:
$$C =\begin{pmatrix}
a_{11}b_{11}+\ldots+a_{1n}b_{n1} & a_{11}b_{11}+\ldots+a_{1n}b_{n2} & \cdots & a_{11}b_{1p}+\ldots+a_{1n}b_{np} \\
a_{21}b_{11}+\ldots+a_{2n}b_{n1} & a_{21}b_{11}+\ldots+a_{1n}b_{n1} & \cdots & a_{21}b_{1p}+\ldots+a_{2n}b_{np} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m1}b_{11}+\ldots+a_{mn}b_{n1} & a_{m1}b_{12}+\ldots+a_{mn}b_{n2} & \cdots & a_{m1}b_{1p}+\ldots+a_{mn}b_{np} 
\end{pmatrix}$$
thus the product $AB$ is defined if and only if the number of columns in $A$ equals the number of rows in $B$

let $A,B\in M_{m\times p}(\mathbb{K}), C,D \in M_{p\times q}(\mathbb{K}), E\in M_{q\times n}(\mathbb{K}), \lambda \in \mathbb{K}$ then:
- $A(CE)=(AC)E$
- $A(C+D)=AC+AD,\ \ (A+B)C = AC+BC$
- $(\lambda A)C = A(\lambda C) = \lambda(AC)$
- $A\omicron = 0A =\omicron$
- $(AC)^T = C^T A^T$
- $AI_p = A$, and $I_pC=C$  [^1]

[^1]: being $I$ the [[identity matrix]]

#matrix 