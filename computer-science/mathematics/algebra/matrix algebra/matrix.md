in mathematics, a matrix is a rectangular [[array]] or table of numbers, symbols or [[expression]]s, arranged in rows and columns

without further specifications, matrices represent [[linear transformation]]s and allow explicit computations in [[linear algebra]][^1]
therefore, the study of matrices is a large part of linear algebra and most properties and operations of abstract linear algebra can be expressed in terms of matrices

matrices with a single row are called row [[vector]] and those with a single column are called column vectors

matrices are generally represented in parenthesis
$$\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix}$$


there are a number of basic operations that can be applied to modify matrices:
- addition: given two matrices with an equal number of rows and columns:
$$A+B=\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix} +\begin{pmatrix}
b_{1,1} & b_{1,2} & \cdots & b_{1,n} \\
b_{2,1} & b_{2,2} & \cdots & b_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
b_{m,1} & b_{m,2} & \cdots & b_{m,n} 
\end{pmatrix} = \begin{pmatrix}
a_{1,1} + b_{1,1} & a_{1,2} + b_{1,2} & \cdots & a_{1,n} + b_{1,n} \\
a_{2,1} + b_{2,1} & a_{2,2} + b_{2,2} & \cdots & a_{2,n} + b_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} + b_{m,1} & a_{m,2} + b_{m,2} & \cdots & a_{m,n}  +b_{m,n} 
\end{pmatrix}$$
- scalar multiplication: it may be viewed as an external binary operation of the field on the vector space:
$$\lambda A=\lambda \times \begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix} = \begin{pmatrix}
\lambda \times a_{1,1} & \lambda \times  a_{1,2}& \cdots & \lambda \times  a_{1,n}\\
\lambda \times a_{2,1} & \lambda \times  a_{2,2} & \cdots & \lambda \times  a_{2,n}  \\
\vdots  & \vdots  & \ddots & \vdots  \\
\lambda \times a_{m,1} & \lambda \times  a_{m,2} & \cdots & \lambda \times a_{m,n}
\end{pmatrix}$$
- transposition[^2]
$$A^T=\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix}^T = \begin{pmatrix}
a_{1,1} & a_{2,1} & \cdots & a_{n,1} \\
a_{1,2} & a_{2,2} & \cdots & a_{n,2} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{1,n} & a_{2,n} & \cdots & a_{n,m} 
\end{pmatrix}$$

these operations have the following properties:
let $A,B,C\in M_{m\times n}(\mathbb{K})$, and let $\lambda,\eta \in \mathbb{K}$ then:
- $A+B=B+A$
- $A+(B+C) = (A+B)+C$
- $(\lambda + \eta) \times A = \lambda \times A + \eta \times A$
- $\lambda (A+B) = \lambda \times A + \lambda \times B$
- $\lambda \times (\eta \times A) = (\lambda \times \eta) \times A$
- $1 \times A = A$
- $(A+B)^T = A^T + B^T$
- $(A^T)^T = A$
- $(\lambda \times A)^T  = \lambda \times A^T$
	let $\omicron \in M_{m\times n}(\mathbb{K})$ be the matrix whose entries are all zeros:
	-  $\omicron + A = A + \omicron = A$
	- $-1 \times A + A = \omicron$
	- $0\in \mathbb{K}, 0\times A = \omicron, \lambda \times \omicron = \omicron$

#matrix

[^1]: not all matrices are related to linear algebra, a [[adjacency matrix]] is an example of this
[^2]: [[transpose matrix]]
