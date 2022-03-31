in coding theory, a parity check matrix of a [[linear code]] $C$ is a [[matrix]] which describes the linear relations that the components of a [[codeword]] must satisfy
it can be used to decide whether a particular [[vector]] is a codeword
it is also used in decoding algorithms

formally:
a parity check matrix $H$ of a linear code $C$ is a [[generating matrix]] of the [[dual code]] $C^{\bot}$ this means that a codeword in $c$ is in $C$ if and only if the matrix-vector product $H_c^{\top} = 0$
the rows of a parity check matrix are the coefficients of the parity check equations

from the definition of the parity check matrix, it directly follows the minimum distance of the code is the minimum number $d$ such that every $d-1$ columns of a parity-check matrix $H$ are linearly independent while there exists $d$ columns of $H$ that are linearly dependent  

#linear_code 