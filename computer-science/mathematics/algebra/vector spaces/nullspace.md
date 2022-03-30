in mathematics, the nullspace of a [[vector space]] is a [[vector subspace]] of another vector that is the solution set which leads to the homogeneous solution of the first set

formally:

let $A\in M_{m\times n}(\mathbb{K})$ be an arbitrary [[matrix]] and let $AX=B$  be a matrix equation representing a [[linear system]] with $m$ equations and $n$ variables $$\begin{pmatrix} a_{11}&a_{12}&\ldots & a_{1n} \\ a_{21}&a_{22}&\ldots & a_{2n} \\ 
\vdots & \vdots &\ddots &\vdots\\
a_{11}&a_{m2}&\ldots & a_{mn} \end{pmatrix}
\begin{pmatrix} x_1 \\ x_2 \\ \vdots \\ x_n \end{pmatrix}
=
\begin{pmatrix} b_1 \\ b_2 \\ \vdots \\ b_n \end{pmatrix}$$
being $W$ the solution [[set]] of the matrix equation $AX=B$
if $B=\omicron \in M_{n\times1}(\mathbb{K})$,$W=\{(\alpha_1,\alpha_2,\ldots\alpha_n)\in \mathbb{K}^n|A\begin{pmatrix}\alpha_1 \\ \alpha_2\\ \vdots \\ \alpha_n \end{pmatrix} = \omicron\} \subseteq \mathbb{K}^n$ 
we can define $W$ as a [[vector subspace]] of $A$, specifically, the nullspace of $A$
otherwise ($b\neq \omicron$), $W$ is not a subspace of $\mathbb{K}^n$

the nullspace can also be called [[kernel]] on all cases, but literature tends to use kernel only if the matrix is representing a [[linear transformation]]

#vector_spaces 