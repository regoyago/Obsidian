there are several indirect demonstrations of the validity of an argument:
- one of them is the contraposition, based on the [[logical equivalence]]s $(p\rightarrow q) \equiv (\neg p\rightarrow \neg q)$
	in our case then, proving that 
	$$H_1 \wedge H_2 \wedge \ldots \wedge H_n \models C$$
	is the same that proving that
		$\neg C \models  \neg (H_1 \wedge H_2 \wedge \ldots \wedge H_n)$, which is, $\neg C \models  (\neg H_1 \vee \neg H_2 \vee \ldots \vee \neg H_n)$.
		
		
- another indirect demonstration is the demonstration by contradiction or reductio ad absurdum, which consist in proving that
$$H_1 \wedge H_2 \wedge \ldots \wedge H_n \wedge \neg C \models \bot $$
since proving that the argument $H_1 \wedge H_2 \wedge \ldots \wedge H_n \models C$ is valid is equal to prove that 
$H_1 \wedge H_2 \wedge \ldots \wedge H_n \rightarrow C$  is a [[tautology]]
which means that its negation:
$H_1 \wedge H_2 \wedge \ldots \wedge H_n \wedge \neg C$  is a contradiction
and {$H_1, H_2, \ldots, H_n, \neg C$} is an inconsistent [[set]]

generally, this method is easily implemented using a [[semantic tableau]]

#mathematical_logic 