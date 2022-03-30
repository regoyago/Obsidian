in mathematics, a [[vector space basis]] of finite dimension allows representing uniquely any element of the vector space, by a coordinate vector
if two different bases  are considered, the coordinate vector that represents the [[vector]] $v$ on one basis is, in general different

thus, a change of basis consists on converting every assertion expressed in terms of coordinates relative to one basis into the same, but relative to the other basis

by using matrices we can write the following formula
$$x_{old}=Ax_{new}$$
being $x$ the column vectors of coordinates of the same vector on respective basis and $A$ the change of basis matrix

formally
let $B_{old}=(v_1,\ldots,v_n)$ be a basis of a finite dimensional vector space $V$ over a [[mathematical field]]
for $j=1,\ldots,n$, one can define a vector $w_j$ by its coordinates $a_{ij}$ over $B_{old}$:
$$w_j=\sum^n_{i=1}a_{ij}v_i$$
let $A=(a_{ij})_{ij}$
be the matrix whose $j$th column is formed by the coordinates of $w_j$

setting $B_{new}=(w_1,\ldots,w_n)$, one has that $B_{new}$ is a basis of $V$ if and only if $A$ is an [[invertible matrix]], in this case $A$ is said to bbe the change-of-basis matrix from the basis $B_{old}$ to  $B_{new}$

given a vector $z\in V$, let $(x_1,\ldots,x_n)$ be the coordinates of $z$ over $B_{old}$ and $(y_1,\ldots, y_n)$ its coordinates over $B_{new}$; that is

$$z=\sum^n_{i=1}x_iv_i=\sum^n_{j=1}y_jw_j$$
the change of basis formula expresses the coordinates over the old basis in term of the coordinates over the new basis:
$$x_i=\sum^n_{j=1}a_{ij} y_j$$ in terms of matrices, the change of basis formula is
$$x=Ay$$
where $x,y$ are the column vectors of the coordinates of $z$ over $B_{old}$ and $B_{new}$

#matrix 
#vector_spaces 