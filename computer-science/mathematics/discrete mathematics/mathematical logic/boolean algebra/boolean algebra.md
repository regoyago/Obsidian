in mathematics an [[mathematical logic]], boolean algebra is a branch of [[algebra]] in which the values of the variables are the [[truth value]]s 

that is while expressions denote mainly numbers, in boolean algebra they denote the truth values represented with the [[bit]]s namely `0` and `1`  for false and true respectively
they do not behave like the integers , but may be identified with the element of [[modular arithmetic]], specifically [[modulo]] 2

the main operations used on [[boolean expression]]s are the same as the ones provided by [[logical connective]]s

there is a strong relation between [[propositional logic]] an boolean algebra, being able to express most of its problems in an algebraic way 
but boolean algebra fails to capture logic formulas using [[first-order logic]]

we define boolean algebra as a [[set]] $A = {a,b,c\ldots}$ with two binary operations: sum ($a+b$) and product ($a*b$), and a unary operation: complement or inversion ($\bar a$), which satisfy the following axioms:
- axiom 1: $A$ is closed for all three operations: $\forall a, b \in A$
	$$a+b\in A \ $$$$  a*b\in A \ $$$$\bar a\in A$$
- axiom 2: there exists two distinguished elements: $0$ and $1$, both $\in A$, such that, $\forall a \in A$:
$$a+0=a \ $$$$ \ a*1=a$$
- axiom 3: for any element $a \in A$, there exists a [[boolean complement]] $\bar a \in A$ such that:
$$a+\bar a = 1 \ $$$$ \ a*\bar a = 0$$
- axiom 4: both the [[boolean sum]] ($+$) and [[boolean product]] ($*$) are [[commutative]]:  $\forall a,b \in A$:
$$a + b = b + a \ $$$$ a * b = b * a $$
- axiom 5: both the sum ($+$) and product ($*$) are [[associative]]:  $\forall a,b,c \in A$:
$$a + (b + c)= (a+b)+c \ $$$$ a*(b*c)= (a*b)*c $$
- axiom 6: the sum operation is [[distributive]] over the product and vice-versa: $\forall a,b,c \in A$:
$$a * (b + c)= (a*b) + (a*c) \ $$$$ a+(b*c)= (a+b)*(a+c) $$


the structure ($A,0,1,+,*,\bar x$) is named boolean algebra

a [[well-formed formula]]) can also be defined as a boolean algebra,  with the [[logical connective]]s, being $\bot$ the $0$ element, and $\top$ the $1$ element  and vice-versa

similarly to [[logical equivalence]], there are some properties on boolean algebra, but substituting each [[logical connective]] with their respective [[boolean operator]]

name | equivalence
-------|---------
commutative laws | $a + b \equiv b + a$
- |  $a* b \equiv b * a$
associative laws | $(a * b) * c \equiv a *(b * c)$$
- | $(a + b) + c \equiv a +(b + c)$
distributive laws | $a* (b + c) \equiv (a* b) + (a * c)$
- |$a+ (b * c) \equiv (a+ b) * (a + c)$ 
double negation law | $\overline {\overline a} \equiv a$
de morgan's laws | $\overline{(a+b)} \equiv \overline a* \overline b$
- | $\overline{(a*b)} \equiv \overline a+\overline b$
domination laws | $a + 1 \equiv 1$
- | $a * 0 \equiv 0$
identity laws | $a + 0 \equiv a$
- | $a * 1 \equiv a$
negation laws | $a + \overline a \equiv 1$
- |  $a * \overline a \equiv  0$
idempotent law | $a \equiv (a + a)$
- | $a\equiv (a*a)$
absorption law | $a + (a* b) \equiv a$
- | $a * (a + b)\equiv a$


#mathematical_logic 
#boolean_algebra
