in [[computational complexity]] theory, $P$, also knwon as $PTIME$  is a fundamental [[complexity class]] that contains all [[decision problem]]s that can be solved by a [[deterministic finite state machine]] in a [[polynomial]] amount of computation time

[[cobham's thesis]] holds that $P$ is the class of computational problems that are "solvable" or "tractable" [^1]

the formal definition of this class is as follows:

a [[formal system]] $L$ is in $P$ if and only if there exists a deterministic turing machine $M$ such that
- $M$ runs for polynomial time on all inputs
- $\forall \ x \ \in \ L$, $M$ outputs $1$
- $\forall \ x \ \notin \ L$, $M$ outputs $0$

it can also be defined as a family of [[boolean circuits]]s, thus, a language $L$ is in $P$ if and only if there exists a polynomial time uniform family of boolean circuits $\{ C_n : n \in \mathbb{N}\}$, such that
- $\forall \ x \ \in \ \mathbb{N}$, $C_n$ takes $n$ bits as input  and returns 1 bit
- $\forall \ x \ \in \ L$ , $C_{|x|}(x) = 1$
- $\forall \ x \ \notin \ L$ $C_{|x|}(x) = 0$

the problems categorized inside this class are closed under composition: if onne writes a function that is  polynomial-time assuming that function calls are constatn-time, and if those called functions themselves require polynomial time, then the entire algorithm takes polynomial time
this categorizes $P$ as [[low]] for itself
languages in $P$ are also closed under reversal, [[intersection]], [[union]], concatenation and such

#computational_complexity 
#complexity_classes

[^1]: this has been found in practice to be inexact, but yields an interesting rule of thumb