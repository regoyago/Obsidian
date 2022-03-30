in linear algebra, the column space (also called range or image) of a [[matrix]] $A$ is the [[linear span]] of its column [[vector]]s

the column space of a matrix is the image or range of the corresponding [[linear transformation]]

formally:
let $\mathbb{F}$ be a [[mathematical field]] and $A$ an $m\times n$ matrix, with column vectors $v_1,v_2,\ldots,v_n$, a [[linear combination]] of these is any vector of the form $$c_1v_1+c_2v_2+\ldots+c_nv_n$$ where $c_1,\ldots,c_n$ are scalars
the set of all possible linear combinations of $v_1,\ldots,v_n$ is called the column space of $A$, that is, the [[linear span]] of the vectors $v_1,\ldots, v_n$

any linear combination of the column vectors of a matrix $A$ can be written as he product of $A$ with the column vector

$$A \begin{pmatrix}c_1\\\vdots\\c_{n}\end{pmatrix} = \begin{pmatrix}a_{1}&\ldots&a_{1n} \\\vdots &\ddots&\vdots\\a_{m1}&\ldots&a_{mn} \end{pmatrix} \begin{pmatrix}c_1\\\vdots\\c_{n}\end{pmatrix}
=
\begin{pmatrix}c_1a_{11}&+\ldots+&c_na_{1n}\\&\vdots\\c_{n}a_{m1}&+\ldots+&c_na_{mn}\end{pmatrix} =$$
$$=
c_1\begin{pmatrix}a_{11}\\\vdots\\a_{m1} + \end{pmatrix} + \ldots+c_n\begin{pmatrix}a_{1n}\\\vdots\\a_{mn}\end{pmatrix}
$$

therefore, the column space of $A$ consists of all possible products $Ax$, for $c\in C^n$, this is the same as the image or range of the corresponding [[linear transformation]]

the columns of $A$ span the column space but they may not form a [[vector space basis]], if the column vectors do not show [[linear independence]]
multiplication by any [[elementary matrix]] does not affect the dependence relations between the column vectors [^1]


[^1]: making [[gaussian elimination]] a suitable operation to find a basis for the column space

#matrix 
#vector_spaces 