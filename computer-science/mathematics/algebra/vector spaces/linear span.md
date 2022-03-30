in mathematics, a linear span or just span is a [[set]] $S$ of [[vector]]s, from a [[vector space]] such that $S$ is the smallest vector space that contains the set

it can be characterised either as the [[intersection]] of all [[vector subspace]]s that contain $S$ or as the [[linear combination]]s of elements in $S$

formally:
let $V$ be a $\mathbb{K}$-vector space
-  a linear combination of $v_1,v_r\in V$ is a vector of the form $w = s_1v_1+s_2v_2+\ldots s_rv_r$, where $s_i\in \mathbb{K}$
- let $S\subset V$ be a nonempty set of vectors of $V$, we write $Span\ S$ to denote the set of all the [[linear combination]]s of vectors in $S$, that is:
$$L(S) = \lambda_1v_1+\ldots + \lambda_tv_t|\lambda_i\in \mathbb{K}, v_i\in S = Span\ S$$
the set $L(S)$[^1] is indeed a vector space

given $V$ a $\mathbb{K}$-vector space, and $S\subset V$ a non-empty set, then $L(S)$ is a vector subspace of $V$, the subspace generated or spanned by $S$

properties of the linear span:
- the subspace spanned by a non-empty subset $S$ of a vector space $V$ is the set of all linear combinations of vectors in $S$
- every spanning set $S$ of a vector space $V$ must contain at least as man elements as any set of vectors from $V$ that display [[linear independence]] 
- let $V$ be a finite-dimensional vector space, any set of vectors that spans $V$ can be reduced to a [[vector space basis]] for $V$, by discarding vectors if necessary
  if the [[axiom of choice]] holds, this is true without the assumption that $V$ has finite dimension[^2]


[^1]: this notation is most commonly found on spanish literature, will be used extensively 
[^2]:   this also indicates that a basis is a minimal spanning set when $V$ is finite dimensional
#vector_spaces 