in order to find the [[greatest common divisor]], apply the [[division]] algorithm to $a$ and $b$, $a=bq+r$ use the property $gcd(a,b)=gcd(b,r)$ and repeat the process for $b$ and $r$ iterate until the process stops  
  
let $a>b>0$, to find $gcd(a,b)$, if $b|a$, then, $gcd(a,b)=b$, if not, we apply the [[division]] algorithm:  
  
- for $a_0=a, a_1=b$ applying division algorithm:  
$a_0=a_1q_1+\overbrace{r_1}^{a_2} \ \ \ \ \ 0\leq r_1<a_1$  
$gcd(a_0,a_1)=gcd(a_1,a_2)$  
- for $a_1, a_2=r_1$ applying division algorithm:  
$a_1=a_2q_2+\overbrace{r_2}^{a_3} \ \ \ \ \ 0\leq r_2<a_2<a_1$  
$gcd(a_1,a_2)=gcd(a_2,a_3)$  
  
  
- the following process is the one to be iterated:  
$a_{n-1}=a_nq_n+\overbrace{r_n}^{a_{n+1}} \ \ \ \ \ \underbrace{0\leq r_n<\ldots<a_1}_*$[1^]  
$gcd(a_{n-1},a_n)=gcd(a_{n+1},a_{n+1})$  
until $a_n=a_{n+1}1_{n+1}+0$  
then, the last nonzero remainder, $r_n$, is the $gcd(a,b)$  
indeed, as $a_{n+1}|n_n \Rightarrow a{n+1} = r_n = gcd(a_n, a{n+1}) = gcd(a_{n-1},a_n)=\ldots=gcd(a_0,a_1)$  
  
  
[1^]:as (*) is a strictly decreasing sequence, bounded below by 0, the algorithm stops  
  
#divisibility 
#arithmetic 