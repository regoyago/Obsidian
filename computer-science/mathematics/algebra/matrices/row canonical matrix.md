a [[matrix]] is said to be in reduced row echelon form (row canonical matrix) if the following conditions are are met:
- it is a [[echelon matrix]]
- each [[pivot]]  is a 1 (called leading 1)
- each column containing a leading 1 has zeros in all its other entries

 example of a row canonical matrix: 
$$\begin{pmatrix}
1 & 0 & 0 & 0 & 0\\
0 & 1 & 0 & 0 & 0\\
0 & 0 & 1 & 0 & 0\\
0 & 0 & 0 & 0 & 1
\end{pmatrix}$$

the reduced row echelon form of a matrix may be computed by [[gaussian elimination]]
unlike the [[echelon matrix]], the row canonical matrix is unique and does not depend on the algorithm used to compute it

#matrix 