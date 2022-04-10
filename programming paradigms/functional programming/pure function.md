in computer programming, a pure function is a [[subroutine]] that has the following properties:  
- the function [[return value]]s are [[identical]] for identical [[argument]]s (there is no variation with local static variables, mutable reference arguments...)  
- the function application has no[[ side effect]]  
  
thus a pure function is a computational analogue of a [[mathematical function]]  
  
pure functions have several useful properties:  
- if the result of a pure expression is not used, it can be removed without affecting other expressions  
- if a pure function is called with arguments that cause no side-effects, the result is constant with respect to that argument list  
- if there is no data dependency between two pure expressions, their order can be reversed or they can be performed in [[parallel]] and they cannot interfere with one another (the evaluation of any pure expression is [[thread-safe]])  
- if the entire language does not allow side-effects, then any evaluation strategy can be used: the compiler can reorder or combine the evaluation of expressions of the program  
  
while most compilers for imperative programming languages detect pure functions and perform common-sub expression elimination for pure function calls, they cannot always do this for pre-compiled libraries  
  
#functional_programming  
#programming_paradigms