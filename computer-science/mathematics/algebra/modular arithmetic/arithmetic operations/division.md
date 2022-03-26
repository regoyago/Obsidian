in arithmetic, division, denoted by the symbol $/$ is essentially the inverse operation to multiplication, it finds the quotient of two numbers,
under common rules, division by zero is undefined, and the property that checks the ability of a number tot be divided is referred to as [[divisibility]]

at an elementary level, the division of two natural numbers is, among other possible interpretations, the process of calculating the number of times one number is contained within another 

division is neither [[commutative]] nor [[associative]]

within the [[natural number]]s, a different but related notion called [[euclidean division]] exists, which outputs two numbers after "dividing them" (the quotient and the reminder)

in some context, including computer programming and advanced arithmetic, division is extended with another output for the remainder, this operation is often treated as a different operation, the [[modulo]]

we can define an [[algorithm]] that performs a division as follows:
given an [[integer number]]s $a$ and another $b$, with $b \neq 0$, there exist unique integers $q (quotient)$ and $r (remainder)$, with $0\leq r < |b|$ such that $a=bq+r$ [^1]  
- $q$,$r$ are unique  
- there are exactly $|b|$ possible remainders  
  
  
proof:  
- existence:  
consider $S=\{t \in\mathbb{Z};bt \leq a\} , S\neq \emptyset$  
if $t\in S$, then $t\leq bt\leq a \Rightarrow$  
- $S$ has an upper bound: $a$, and $S \in\mathbb{Z}$  
- $S$ admits a maximum element: $q:=maxS \Rightarrow$  $$bq\overbrace{\leq}^{q \in\mathbb{Z}} a \overbrace{<}^{q=maxS} b(q+1) \Rightarrow 0\leq a - bq<b$$  for $r=a-bq$, the division algorithm holds  
- uniqueness:  
supposing that $a=bq_1+r_1, a=bq_2+r_2$  
then $q_1\neq q_2 r_1\neq r_2$  
  
#divisibility  
  
[^1]: we are applying the concept of [[divisor]] and basically formally defining the division


#arithmetic