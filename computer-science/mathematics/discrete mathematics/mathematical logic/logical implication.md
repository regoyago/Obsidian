in [[mathematical logic]], implication (also known as logical consequence) is the relationship between [[statement]]s that holds true when one logically "follows from" one or more others

given two [[statement]]s $P$ and $Q$, it is said that $P$ implies $Q$, or that you can deduce $Q$ from $P$, when the composite statement $P\rightarrow Q$ is a [[tautology]] ($\top$).
this means that when $P$ is true, $Q$ will also be true and when $P$ is false, $Q$ will also be false.
this is denoted as:

$$P\models Q$$

it can also be denoted as $P\implies Q$
noting that "$\rightarrow$" and "$\implies$" are very different things:
$P\implies Q$ denotes that the statement $P \rightarrow Q$  is always true ($\top$), while $P \rightarrow Q$ just denotes a composite statement.

moreover, $P\implies Q$ is not an [[well-formed formula]]


the most commonly known logical implications are the following:

name | implication
-------|--------
modus pollens | $[(p\rightarrow q) \wedge p] \models q$
modus tollens | $[(p\rightarrow q) \wedge ¬q]\models ¬p$
syllogism | $(p\rightarrow q) \wedge) (q \rightarrow r)] \models (p\rightarrow r)$
simplification laws | $(p \wedge q)\models p$
- | $(p \wedge q)\models q$
addition laws | $p \models (p \vee q)$
- | $q \models (p\vee q)$
disyuntive syllogism | $((p\vee q)\wedge ¬p)\models q$
- | $((p\vee q) \wedge ¬q)\models p$
law of cases | $[(p\rightarrow q) \wedge(¬p\rightarrow q)]\models q$
inconsistency law | $(p\wedge ¬p)\models q$

#mathematical_logic 