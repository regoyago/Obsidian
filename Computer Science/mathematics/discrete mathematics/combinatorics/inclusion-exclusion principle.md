in its simplest form, this principle states that:
given two sets $A$ an $B$, each a finite [[set]], then:

$$|A\cup B|=|A|+|B|-|A\cap B|$$

the reason behind this formula is that, if we were define the $A\cup B$ as the cardinal of both $A$ and $B$, if there were some element that belong to both elements, they would be counted twice, thus we need to subtract one those elements that are on both (since they have been counted twice already)

given the same principle for three different sets $A, B, C$:

$$|A\cup B \cup C|=|A|+|B|+|C|-(|A\cap B|+|B\cap C|+|A\cap C|)+|A \cap B \cap C|$$


with these definitions we can make a general definition of the principle:
given $S$, a finite set, and $P_1,P_2,\ldots ,P_n$ properties of the elements in S, the subsets $S_i$ of $S$ are defined as :

$S_i= \{x\in S | x$ verifies the property $P_i\}, i=1,2,\ldots ,n$

we can define two complementary sets: $\overline{\bigcup_{i=1}^{n}}$ =$\bigcap_{i=1}^{n}$

- $\bigcup_{i=1}^{n}S_i=\{x\in S$ verifies any property $P_i\}$
- $\bigcap_{i=1}^{n}\bar{S_i}=\{x\in S$ doesn't verify any property $P_i\}$


expanding both definitions:

-	$|\bigcup_{i=1}^{n}S_i|=$ $=\sum_{i=1}^{n}|S_i|-\sum_{1\leq i<j\leq n}|S_{i}\cap S_{j}|+\ldots +(-1)^n|S_{1}\cap \ldots \cap S_{n}|=$ $=|S|+\sum_{k=1}^{n}(-1)^{k} \sum_{1\leq i_1<i_2<\ldots <i_k\leq n}|S_{i_1}\cap S_{i_2}\cap \ldots \cap S_{i_k}|$

-	$|\bigcap_{i=1}^{n}\bar{S_i}| =$ $=|S|-\sum_{i=1}^{n-1}|S_i|-\sum_{1\leq i<j\leq n}|S_{i}\cap S_{j}|+\ldots +(-1)^n|S_{1}\cap \ldots \cap S_{n}|=$ $=|S|+\sum_{k=1}^{n}(-1)^{k} \sum_{1\leq i_1<i_2<\ldots <i_k\leq n}|S_{i_1}\cap S_{i_2}\cap \ldots \cap S_{i_k}|$

in order to prove the first equality, we take any element $x\in S$ and we check that it is "counted" as many times in the right part of the equation as in the left
- if $x$ doesn't satisfy any property $P$, that is, $x\in \bigcap_{i=1}^{n}\bar{S_i}$ and contributes with a 1 on the left side. 
also, $x\in S$, but $x\notin S_{i_1}\cap S_{i_2}\cap \ldots \cap S_{i_k}$, for all $i_1>\ldots>i_k$ and for all $k$
then $x$ will also be counted one in the right part of the equality

- if $x$ satisfies $m$ of $n$ properties ($m\leq n$), this means, $x$ belongs to $m$ of the $n$ sets $S_i$
since $x$ doesn't belong to $\bigcap_{i=1}^{n}\bar{S_i}$, $x$ contributes with a 0 on the left part of the equality
moreover, $x$ will contribute with a 1 on $|S|$, with $m$ on the sum $\sum_{i=1}^{n}|S_i|$, once for each set in which it belongs
in general, for each natural $k$, $1\leq k\leq m$, $x$ belonging to $\binom{m}{k}$ intersections that follow $S_{i_1}\cap S_{i_2}\cap \ldots \cap S_{i_k}$, the possible [[combination]] of order $k$ of the $m$ sets
for all this, $x$ contributes with a total of:
$1+\sum^{m}_{k=1}(-1)^k\binom{m}{k}=(1+(-1))^m=0$


#combinatorics 