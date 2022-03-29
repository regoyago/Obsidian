in mathematics, the determinant is a [[mathematical function]] of the entries of a [[square matrix]]
it allows characterising some properties of the given matrix, namely, the determinant is non-zero if and only is the matrix is an [[invertible matrix]]

we give a definition of the determinant using  [[recursion]]: we define the determinant of an $n\times n$ matrix using the determinant of $(n-1)\times (n-1)$ submatrices

let $A$ be am $n\times n$ matrix $(n\geq 2)$
denote by $A_{i1},A_{i2},\ldots ,A_{in}$ the submatrices of $A$ contained by deleting row $i$ and, respectively, column $1$,$2$, up to $n$[^1]
- for $A=(a_{ij})$ we define $det(A)=a_{ij}$, an $n\times n$ matrix, we define the determinant as
$$detA=a_{i1}detA_{i1}-a_{i2}detA_{i2}+\ldots+(-1)^{1+n}a_{in}detA_{in}$$
the number $C_{ij} = (-1)^{i+j} det A_{ij}$ is called the $(i,j)$-cofactor of $A$, and we can use it to express the determinant as:$$det A = a_{i1}C_{i1}+a_{i2}C_{i2}+ \ldots + a_{in}C_{in}$$
where $i$ can be any row[^1]

thus, we can ensure that the determinant of an $n\times n$ matrix $A$ can be computed by a cofactor expansion across any row or down any column:
- the expansion across the $i$th row using cofactors is:$$det A = a_{i1}C_{i1}+a_{i2}C_{i2}+ \ldots + a_{in}C_{in}$$
- the expansion across the $j$th column is:$$det A = a_{1j}C_{1j}+a_{2j}C_{2j}+ \ldots + a_{nj}C_{nj}$$
from this we can derive that the determinant of a matrix that has either a zero row or a zero column is zero
and that the determinant of a [[triangular matrix]] or [[diagonal matrix]] is the product of the elements in the diagonal
$$det A = a_{11}a_{22}\ldots a_{nn}$$
moreover we can derive that th determinant of a matrix $A$ will always be the same as its [[transpose matrix]] $A^T$

the determinant of a matrix has the following properties:
- if $A$, $B$ are matrices of the same size, then $detAB = detA \times detB$[^3]
- if two rows of $A$ are interchanged $detA$ changes sign 
- if a row of $A$ is multiplied by $\lambda$, $detA$ is also multiplied
- if a multiple of one row of $A$ is added to another row, then the determinant is left unchanged [^4]
- if $A$ has two equal rows, its determinant is $0$
- if $A$ has a row that is a [[linear combination]] of another, the determinant is $0$


[¹]: that is, $A_{ij}$ denotes the submatrix of $A$ obtained by deleting the $i$-th row and the $j$-th column
[^2]: note that this can also be performed if taking columns into account instead of rows
[^3]: this property does not tend to hold for the sum 
[^4]: each of these is equivalent to multiply by an [[elementary matrix]], and as expected, the results are the same if we talk about columns

#matrix 