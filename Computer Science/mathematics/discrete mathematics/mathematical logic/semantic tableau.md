a semantic tableau, also known as truth trees is a decision procedure computed for a logical formula, which has, at each node, a subformula of the original formula, which aims to schematize the [[semantics of logic]] of a set of statements
the tableau is build up by following a set of rules:
- the conjunction ($\wedge$) is represented as a vertical  line following all current branches with both statements 
- the disjunction ($\vee$) is represented as a bifurcation in all current branches with one statement in each new branch
- the conditional ($\rightarrow$) is represented as a bifurcation with the opposite of the first statement in one branch and the second statement in the other
- the biconditional ($\leftrightarrow$) is represented as a bifurcation winch contains the conjunction of both statements in one branch and the conjunction of their opposites in the other



semantic tableau are commonly used in order to determine the [[logical consistency]] of a [[set]] of statements:
in order to check if a set of statements {$P_1,P_2,...,P_n$} is consistent, the semantic tableau of $P_1\wedge P_2 \wedge \ldots \wedge P_n$ is built, and one by one, we break down all its composite propositions, following the rules aforementioned. If in a branch there appear both a statement and its negative, it is said to be a closed branch, and is marked with a ( * ) the final node.
if at the end of the process, all branches all closed, the formula $P_1\wedge P_2 \wedge \ldots \wedge P_n$ is a contradiction (the set  {$P_1,P_2,...,P_n$} is inconsistent):
any open branch represents a model of $P_1\wedge P_2 \wedge \ldots \wedge P_n$, if there is at least one,  {$P_1,P_2,...,P_n$} is consistent

#mathematical_logic 