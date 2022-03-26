in [[computational complexity]] theory, a problem can be classified as NP-complete when
- it is a problem for which the correctness of each solution can be verified quickly (in polynomial time) and a [[brute-search algorithm]] can fins a solution by trying all possible solutions
- the problem can be used to simulate every other problem for which we can verify that a solution s correct, thus [[NP]]-complete problems are the hardest of the problems to which solutions can be verified quickly and if we could find such solution for one of these problems, we could find the solution to all of them

formally a NP-complete problem $C$  can be defined as follows:
- $C \in NP$ 
- every problem in $NP$ can be reduced by a [[many-one reduction]] to $C$ in polynomial time[^1]
$C$ can  be shown to be in $NP$ by demonstrating that a candidate solution to $C$ can be verified in polynomial time

#computational_complexity 
#complexity_classes 

[^1]: note that any problem that checks condition 2, whether or not it checks condition 1, it can be classified as NP-hard