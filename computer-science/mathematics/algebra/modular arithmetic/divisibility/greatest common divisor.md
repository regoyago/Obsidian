let $a$, $b$ be non-zero [[integer number]]  
- $d$ is the greatest common divisor of $a$ and $b$, denoted as $gcd(a,b)$, if $d$ is the largest [[common divisor]] of $a$ and $b$  
  
  
$\forall a, b \in \mathbb{Z}, \ \exists gdc(a,b)$:  
- $D_a$ is always a finite [[set]], $d \in D_a$, $-|a|\leq d \leq |a|$  
- $D_b$ is always a finite [[set]], $d \in D_b$, $-|b|\leq d \leq |b|$  
hence, $D_a\cap D_b$ is a finite [[set]], and it admits a maximum  
- $d\geq 1 \Rightarrow gcd(a,b)$ is always a positive number  

we can state the following lemma:
let $a>b$ two positive integers, then, if $a=b1+r$ with $0\leq r < b$ we have that: $$gcd(a,b) = gcb(b,r)$$
- proof:
 (prove that $gcd(a,b)\overbrace{=}^*gcd(a-b,b)$):  
 by using the lemma stated on [[divisor]]:  $D_a \cap D_b \overbrace{=}^{lemma 1}D_{a-b}\cap D_{b}\Rightarrow *$ holds  
 iterating: $gcd(a-b,b)\overbrace{=}^*gcd(a-2b,b)=\ldots = gcd(a-bq,b)\overbrace{=}^{r=a-bq}gcd(r,b)$

#divisibility
#arithmetic