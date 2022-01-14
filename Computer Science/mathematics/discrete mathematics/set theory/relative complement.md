in [[set theory]], we define as relative complement or set difference as the [[set]]  that are in one set but not in the other

if $A$ and $B$ are sets, then the relative complement of $A$ in $B$ , denoted as $B\backslash A$ such that
$$B\backslash A = \{x\in B : x \notin A\}$$

it has the following properties:
let $A$, $B$, $C$ be sets:
- $C\backslash (A\cap B) = (C\backslash A)\cup (C\backslash B)$ 
- $C\backslash (A\cup B) = (C\backslash A)\cap (C\backslash B)$ 
-  $C\backslash (A\backslash B) = (C\cap A)\cup (C\backslash B)$ 

-  $(B\backslash A)\cap C = (B\cap C) \backslash A = B\cap (C\backslash A)$
-  $(B\backslash A)\cup C = (B\cup C) \backslash (C\backslash A)$
-  $A\backslash A = \emptyset$
-  $\emptyset \backslash A = \emptyset$
-  $A\backslash U = \emptyset$
-  if $A\subset B$ then $C\backslash A \supset C\backslash B$ 
-  $A \supseteq B\backslash C$ is equivalent to  $C\supseteq B\backslash A$

to define the relation we can define the [[complementary relation]]

#set_theory