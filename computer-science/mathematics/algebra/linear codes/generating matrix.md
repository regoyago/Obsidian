in coding theory, a generator matrix is a [[matrix]] whose rows form a [[vector space basis]] for a [[linear code]]
the codewords are all of the [[linear combination]]s of the rows of this matrix, that is, the linear code is the [[row space]] of its generator matrix

formally:
if $G$ is a matrix, it generates the [[codeword]]s of a linear code $C$ by 
$$w = sG$$
where $w$ is a codeword of the linear code $C$ and $s$ s any input vector
both $w$ and $s$ are assumed to be row vectors
a generator matrix for the linear $[n,k,d]_q$-code has format $k\times n$, where 
- $n$ is the length of a codeword
- $k$ the number of information bits (dimension of $C$ as a [[vector subspace]])
- $d$ the minimum distance of the code
- $q$ size of the finite [[mathematical field]] (the number of symbols in the alphabet)

when  $G$ has the block matrix form $G=[I_k|P]$,
(where $I_k$ denotes the $k\times k$ [[identity matrix]] and $P$ is some $k\times (n-k)$ matrix, then we say $G$ is in standard form, in this case, the code $C$ is said to be [[systematic code]] in its first $k$ coordinate positions

a generator matrix can be used to construct the [[parity check matrix]] for a code 

#linear_code 