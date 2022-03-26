in [[computational complexity]] theory, $NP$,  is a fundamental [[complexity class]] defined as the [[set]] of the decision problems for which the problem instances, where the answer is favourable, have proofs verifiable in [[polynomial]] time by a [[deterministic finite state machine]], or alternatively the set of problems that can be solved in polynomial time by a [[non-deterministic finite state machine]]

this definition is the origin of the abbreviation name "Non-deterministic Polynomial time"

it is easily observable that the complexity class [[P]] is contained in $NP$, because if a problem is solvable in polynomial time, then a solution is also verifiable in polynomial time, just by solving the problem 
yet there are some problems known to be contained in $NP$ that for the time being have not been able to be also classified in $P$, specially [[NP-complete]] problems

this complexity class is closely related to the [[co-NP]] class, for which the answer "no" can be verified in polynomial time, whether $NP = co-NP$ is another question in [[computational complexity]]

$NP$ can be defined in terms of [[NTIME]] as follows:
$$NP = \bigcup_{k\in \mathbb{N}}NTIME(n^k)$$
where $NTIME(n^k)$ is the [[set]] of decision problems that can be solved using a [[non-deterministic finite state machine]] in $O(n^k)$ time

alternatively, $NP$ can be defined using deterministic turing machines as verifiers
a [[formal system]] $L$ is in $NP$ if and only if there exists polynomials $p$ and $q$, and a deterministic turing machine $M$ such that
- $\forall x, y$ the machine $M$ runs in time $p(|x|)$ on input $(x,y)$
- $\forall x, y \in L$, there exists a string $y$ of length $q(|x|)$ such that $M(x,y)=1$
- $\forall x \notin L$ and all strings $y$ of length $q(|x|)$, $M(x,y) = 0$

because of the many important problems in this class, there have been extensive efforts to find polynomial-time algorithms for problems in $NP$, however there remain a large number of problems in $NP$ that defy such attempts

languages in $NP$ are also closed under reversal, [[intersection]], [[union]], concatenation , but it is not known if the same is true for the complement[^1]

#computational_complexity 
#complexity_classes

[^1]: for this to be true ,  [[co-NP]] = [[NP]] must be true