in [[mathematical logic]], two statements $p$ and $q$ are said to be logically equivalent if they have the same truth value in every model

the logical equivalence of $p$ and $q$ is sometimes expressed as $p \equiv q$,  or $p::q$, depending on the notation being used

general logical equivalences:

name | equivalence
-------|---------
commutative laws | $p\vee q \equiv q \vee p$
- |  $p\wedge q \equiv q \wedge p$
associative laws | $(p\vee q) \vee r \equiv p\vee(q\vee r)$
- | $(p\wedge q) \wedge r \wedge p\wedge(q\wedge r)$
distributive laws | $p\vee (q \wedge r) \equiv (p\vee q)\wedge (p\vee r)$
- | $p\wedge (q \vee r) \equiv (p\wedge q)\vee (p\wedge r)$ 
double negation law | $¬¬p \equiv p$
de morgan's laws | $¬(p\vee q) \equiv (¬p\wedge ¬q)$
- | $¬(p\wedge q) \equiv (¬p\vee ¬q)$
domination laws | $p\vee \top \equiv \top$
- | $p\wedge \bot \equiv \bot$
identity laws | $p\wedge \top \equiv p$
- | $p\vee \bot \equiv p$
negation laws | $p \vee ¬p \equiv \top$
- |  $p \vee ¬p \equiv \bot$
contraposition law | $(p\rightarrow q) \equiv (¬q\rightarrow ¬p)$
implication law | $(p\rightarrow q) \equiv (¬p\vee q)$
- | $¬(p\rightarrow q \equiv (p \wedge ¬q))$
equivalence law | $(p\leftrightarrow q) \equiv [(p\rightarrow q) \wedge (q \rightarrow p)]$ 
- |  $(p\leftrightarrow q) \equiv (p\wedge q) \vee (¬p \wedge ¬q)$ 
idempotent law | $p\equiv (p \vee p)$
- | $p\equiv (p\wedge p)$
absorption law | $p\wedge (p\vee q) \equiv p$
- | $p \vee (p\wedge q)\equiv p$
reductio ad absurdurm | $(p\rightarrow q) \equiv [(p \wedge¬q)\rightarrow \bot]$

#mathematical_logic 