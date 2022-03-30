let $\mathbb{K}$ be a [[mathematical field]] (for us $\mathbb{K}=\mathbb{Q},\mathbb{R},\mathbb{Z}_p$, p a [[prime]] number)  
  
let $V, W$ be both a $\mathbb{K}$-[[vector space]] and let $T : V \rightarrow W$ be a [[map]]  
we say that $T$ is a $\mathbb{K}$-linear transformation (or a linear transformation), if for every $u,v \in V, s \in \mathbb{K}$:  
- $T(u+v)=T(u)+T(v)$  
- $T(su)= sT(u)$  
these conditions are equivalent to check if the following equality holds:  
- $T(su+rv)=T(su)+T(rv)=sT(u)+rT(v)$  
  
  
a linear transformation will have the following properties:  
- $T(s_1 u_1+\ldots + s_n u_n) = s_1T(u_1)+\ldots +s_nT(u_n)$  
- $T(0_v)=0_w$  
- $T(-v)=-T(v)$  
- given the linear transformation $T: V\rightarrow W$ and the [[set]] $B={v_1,\ldots ,v_n}$, a [[vector space basis]] of $V$, then $T$ is completely determined by the images $T(v_1),\ldots , T(v_n)$  
proof that $S(v)=T(v) \forall v\in V$  
we take an arbitrary $v \in V$: since $B$ is a basis, there exists $a_1,\ldots , a_n \in \mathbb{K}$ such that $v=a_1v_1+\ldots + a_nv_n$  
then, using that $S$ is linear, we have that  
$$S(v)=a_1S(v1)+\ldots +a_nS(v_n)=a_1T(v_1)+\ldots + a_nT(v_n)=T(v)$$  
  
#linear_transformations