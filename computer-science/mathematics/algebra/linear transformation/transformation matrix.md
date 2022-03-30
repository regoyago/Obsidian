in linear algebra, a [[linear transformation]]s  can be represented by a [[matrix]]

if $T$ is a linear transformation mapping $\mathbb{R}^n \rightarrow \mathbb{R}^m$ and $x$ is a column vector with $n$ entries, then
$$T(x)=Ax$$
for some $m\times n$ matrix $A$ called the transformation matrix of $T$

formally:

let $V$ and $W$ be [[vector space]] each and $B_v=\{v_1,\ldots,v_n \}$ and $B_w=\{w_1,\ldots,w_n \}$ [[vector space basis]] for $V$ and $W$ respectively:  
let $T:V\rightarrow W$ be a [[linear transformation]], we associate a [[matrix]] $M_{B_vB_w}(T)$ as follows:  
  
if $T(v_j)=a_{1_j}w_1+\ldots a_{m_j}w_m, a_{ij} \in \mathbb{K}$ for $i=1,\ldots ,m$ $j=1,\ldots ,n$ then  
  
$T=\begin{pmatrix} a_{1i}\\ \vdots \\ a_{mi} \end{pmatrix}$ and the associated matrix with respect to $B_v$ and $B_w$ is:  
$$M_{B_vB_w}(T)=([T(v_1)]_{B_w}|\ldots |[T(v_n)]_{B_w}) \in M_{m\times m} \mathbb{K}$$   
  
worth noting property: $[T(v)]_{B_w}=M_{B_vB_w}(T).[v]_{B_v}$  

#linear_transformations  
#matrix 
