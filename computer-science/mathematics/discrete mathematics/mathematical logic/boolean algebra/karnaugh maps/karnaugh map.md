in [[boolean algebra]], a karnaugh map, or simply k-map of a [[boolean function]] is an alternative way of presenting the same information stored in a [[truth table]];

it consists of a grid whose number of cells depends on  the number of variables of the given function

in each box, the value of the adequate variable will be represented, since there is a correspondence between the grid and each variable
the total number of boxes would be $2^n$, being $n$ the number of variables in the function

in order to decide whether to represent a variable with 1 or 0:
if the [[conjunctive normal form]] is given , we will assign a 0 to each cell that appears in it, if the given is the [[disjunctive normal form]], we will assign a 1 to each cell that appears in it

two cells are said to be adjacent if its products (or sums) of literals that they represents are exactly equal except for only one literal.
in a k-map, adjacent cells are represented physically adjacent vertically and horizontally

to simplify a function represented in a k-map, we must group adjacent cells inside a closed line, and then we must calculate the corresponding simplification.
the objective is to identify the biggest blocks of cells and to cover as many $1$ as possible with the less possible number of blocks:
- two adjacent cells simplify a variable
- four adjacent cells simplify two variables
- and so on...

the "blocks" obtained will be named implicants of the function to minimize
an implicant is said to be prime, if it is not inside a bigger implicant 
a prime implicant is said to be essential if it covers a $1$ that wouldn't be covered without it 

#mathematical_logic 
#boolean_algebra 