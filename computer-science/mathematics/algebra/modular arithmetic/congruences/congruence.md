let $m$ be a positive [[integer number]]s, if $a$ and $b$ are integers:  
- we say that $a$ is **congruent** to $b$ [[modulo]] $m$ if $m|a-b$  
we write $a\equiv b \ \ mod \ m$  
- if $m\nmid a-b$ we say that $a$ and $b$ are **incongruent** [[modulo]] m  
we write $a\not\equiv b \ \ mod \ m$  
  
  
given $m$ it is assured that congruence [[modulo]] $m$ will satisfy the following properties:  
- reflexive $a \equiv a\ mod\ m \ \ \ \ \ \forall a \in \mathbb{Z}$  
proof: $m|a-a \ \ \ \ \forall a \in \mathbb{Z}$  

- symmetric $a \equiv b\ mod\ m \iff b\equiv a \ mod \ m \ \ \ \ \ \forall a,b \in \mathbb{Z}$  
proof: $a\equiv_m b \iff a-b = k.m \iff b-a = m(-k)\iff m|b-a \iff b\equiv_m a$  
  
  
- transitive:$$\begin{equation}  
\left. \begin{aligned}  
a \equiv b\ mod\ m\\  
b \equiv c\ mod\ m  
\end{aligned}  
\right\}  
\qquad {a\equiv c\mod \ m \ \ \ \ \ \forall a,b,c \in \mathbb{Z}}  
\end{equation}$$  
proof:  $$\begin{equation}  
\left. \begin{aligned}  
\text{if }\ a \equiv_m b\ \implies m|a-b \implies \exists k;\ a-b=mk\\  
\text{and }\ b \equiv_m c\ \implies m|b-c \implies \exists k';\ b-c=mk'  
\end{aligned}  
\right\}  
\qquad {(a-b=mk)+(b-c=mk')  
\implies}  
\end{equation}$$$$\implies a-c=m(k+k')\implies m|a-c\implies a\equiv_m c$$  
  
#congruences