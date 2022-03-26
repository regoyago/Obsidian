a linear congruence in one variable is an expression of the form  
$$ax\equiv b mod m (*)$$  
where x is an unknown and $a,b$ and $m>1$ are integers  
  
it is worth noting that if $x_0$ is a solution of ($*$) and $x_1\equiv_m x_0$, then $x_1$ is also a solution  
proof:$$\begin{equation}  
\left. \begin{aligned}  
ax_0\equiv b\ mod\ m\\  
ax_1\equiv ax_0\ mod\ m  
\end{aligned}  
\right\}  
\qquad {ax_1\equiv b\ mod\ m}  
\end{equation}$$  

moreover; for $a,b,m > 1$ integers, let $d = gcd(a,m)$ and consider the linear congruence $ax\equiv_m b$  
- if $d \nmid b$, then $ax\equiv_m b$ has no solutions  
- if $d|b$ then $ax\equiv_m b$ has exactly $d$ incongruent solutions modulo $m$  
moreover, if $x_0$ is a particular solution, a complete [[set]] of incongruent solutions is of the form  
$$x_t=x_0+\frac{m}{d}t, t=0,\ldots,d-1$$
proof: $$ax\equiv_m b\ \text{ is solvable}\ \iff \exists x_0 \in \mathbb{Z}\ \text{ such that }\ ax_0\equiv_m b \iff m|ax_0-b$$ by definition of [[congruence]]:  $$\iff \exists x_0 \in \mathbb{Z}, \exists y_0 \in \mathbb{Z}\ \text{ such that }\ m.y_0=ax_0-b$$ by definition of [[divisor]]:  $$\iff \exists x_0 \in \mathbb{Z}, \exists y_0 \in \mathbb{Z}\ \text{ such that }\ ax_0+m(-y_0)=b$$ $$gcd(a,m)|b$$  with this, it has been proven that:  
$ax\equiv_m b$ is solvable $\iff$ the linear [[diophantine equation]] is solvable, and also, if $x_0$ is a particular solution to $ax\equiv_m b$, then all the solutions are of the form $x_t=x_0\frac{m}{gcd(a,m)}t, t\in \mathbb{Z}$  
  
supposed $x_s=x_0+\frac{m}{gcd(a.m)}s$ and $x_t=x_0+\frac{m}{gcd(a,m)}t$ are congruent mod $m$  
then: $$x_0+\frac{m}{gcd(a,m)}s \equiv_m x_0+\frac{m}{gcd(a,m)}t \implies \frac{m}{gcd(a,m)}s \equiv_m \frac{m}{gcd(a,m)t}$$  $$\iff m|\frac{m}{gcd(a,m)}s - \frac{m}{gcd(a,m)}t \iff m|\frac{m}{gcd(a,m)}(s-t)\implies \overbrace{gcd(a,m)}^d|(s,t)$$  $$\iff s\equiv_d t $$  
therefore, $x_s\equiv_m x_t \iff s\equiv_d t$, which means that there exist exactly $d$ incongruent solution  
  
#congruences