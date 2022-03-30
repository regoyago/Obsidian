in [[vector space]] theory, a [[set]] of [[vector]]s is said to be linearly independent is there is a nontrivial [[linear combination]] of the vectors that equals the zero vector
if no such linear combination exists, then the vectors are said to be linearly independent [^1]

formally:
a set of vectors $\{v_1,v_2,\ldots v_r\}$ in $V$ is said to be linearly independent if the vector equation 
$$c_1+v_1+c_2+v_2+\ldots+c_rv_r = \omicron$$
has only the trivial solution $c_1=\ldots=c_r=0$

the set $\{v_1,v_2,\ldots,v_r\}$ is said to be linearly dependent if the previous equation has a nontrivial solution, that is, f there are some $c_1,\ldots,c_r$ different from zero such that the equation holds
in that case, the given equation is called a linear dependence relation among $v-1,v_2,\ldots,v_r$

remarks:
- a set of a single vector is linearly independent if and only if it is not the zero vector
- a set of two vectors is linearly dependent if and only id one of the vectors is a scalar multiple of the other
- any set containing the zero vector is linearly dependent
- 
this definition can also be expressed with matrices leading to the following extra remarks:
in general, for $A\in M_{m\times n}(\mathbb{K})$:
- if the [[linear system]] $AX = 0$ is a has a solution, then the set of all the columns of $A$ is a linearly independent set of $\mathbb{K}^m$
- else ($AX=0$ is an [[undetermined system]]), then the set of all columns of $A$ is a linearly dependent set of $\mathbb{K}^m$

moreover, a set $S = \{v_1,\ldots ,v_r\}$ of two or more vectors is linearly dependent if and only id some $v_j$ is a linear combination of the rest
thus:
let $S = \{v_1,\ldots ,v_r\}$$ be a linearly independent set and $v\notin L(S)$, then$$S\cup\{v\}  = \{v_1,\ldots ,v_r, v\}$$ is also linearly independent 

#vector_spaces 

[^1]: the definition of [[vector space dimension]] is built upon these concepts