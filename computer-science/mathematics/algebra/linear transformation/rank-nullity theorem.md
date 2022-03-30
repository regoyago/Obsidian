the rank nullity theorem is a theorem in linear algebra that asserts that the dimension of the [[domain]] of a [[linear transformation]] is the sum of its [[column space]] and its [[nullspace]]

formally;
let $T:V\rightarrow W$ be a [[linear transformation]] between two [[vector space]]s where $T$'s [[domain]] $V$ is finite dimensional
then:
$$rk(T) + Null(T) = dim(V)$$
  

it must be noted that, given $T: \mathbb{K}^n\rightarrow \mathbb{K}^m$ , a [[linear transformation]], then :  
- if $n>m, T$ cannot be an [[injection]]  
$T$ is injective if, and only if $Ker(T)={0_v}$ hence $dim Ker(T)=0$ and $$n=dim\ ker(T)+rk(T)=rk(T)\leq m \underbrace{< n}_{\text{hypothesis}}$$ we reach a contradiction ($n<n$), thus, $T$ cannot be injective  
  
  
- if $n<m, T$ cannot be a [[surjection]]  
$T$ is surjective if, and only if $Im(T)=\mathbb{K}^m$ hence $rk(T)=m$ and$$n=dim\ ker(T)+rk(T)=dim\ ker(T)+m\geq m \underbrace{> n}_{\text{hypothesis}}$$ we reach a contradiction ($n>n$), thus, $T$ cannot be surjective  
  
thus it can be deduced that only if $n=m, T$ will be a [[bijection]]  
  
#linear_transformations