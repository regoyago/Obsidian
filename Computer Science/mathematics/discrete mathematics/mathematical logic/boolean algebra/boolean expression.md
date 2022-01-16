starting from the set of symbols stated in [[boolean algebra]] and a [[set]] of [[boolean literal]], we can define a language similar to that of an [[well-formed formula]], making the needed changes already stated in [[boolean algebra]].

given the boolean algebra $A=\{0,1\}$, a variable $x$ is a boolean variable if it takes values from $A$

this variables behave as it would be expected from the [[modular arithmetic]] with [[modulo]] 2

boolean expressions with variables $x_1,\ldots x_n$ are recursively defined as follows:
- $0,1,x_1,\ldots x_n$ are boolean expressions
- if $E_1$ and $E_2$ are boolean expressions, then $\bar E_1, E_1+E_2, E_1*E_2$ are, too, boolean expressions

the following hierarchy is established:
- [[boolean complement]]
- [[boolean product ]]
- [[boolean sum]]

this way,  $(x_1*x_2)+x_3$ is written as $x_1*x_2+x_3$, but the expression $(x_1*x_2)+x_3$ differs from $x_1*x_2+x_3$

it is important to remark the similarity with a [[well-formed formula]] in logic, but here there is a different hierarchy level on ($+, *$), not shared with their logic equivalents ($\vee, \wedge$)

#mathematical_logic 
#boolean_algebra