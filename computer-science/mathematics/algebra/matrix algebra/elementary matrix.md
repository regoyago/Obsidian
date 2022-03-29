in mathematics an elementary matrix is a [[matrix]] which differs from the [[identity matrix]] by one single elementary row operation

elementary row operations are used in [[gaussian elimination]] to archive the [[echelon matrix]] or [[row canonical matrix]]

there are three types of elementary matrices, which correspond to three types of row operations[^1]
- row switching: a row within the matrix is switches with another row
	$R_i\leftrightarrow  R_j$
- row multiplication: each element in a row can be multiplied by a non-zero constant:
	$\lambda R_i \rightarrow R_i$, where $\lambda \neq 0$
- row addition: a row can be replaced by the sum of that row and a multiple of another:
	$R_i+ \lambda R_j \rightarrow R_i$, where $i\neq j$

if $E$ is an elementary matrix, to apply the elementary row operation to a matrix $A$, one multiplies $A$ by the elementary matrix on the left ($EA$)

the elementary matrix for any row operation is obtained by executing the operation on the identity matrix

an elementary matrix  is always an [[invertible matrix]], and its inverse,, is an elementary matrix of the same type that transforms $E$ back into $I_n$[^2]

[^1]: this is the explanation for the applicable operations on [[linear system elementary operation]]s
[^2]: this can be used in order to find the inverse of an [[invertible matrix]]

#matrix