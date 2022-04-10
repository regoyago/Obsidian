in computer science, recursion is a method of solving a problem where the solution depends on solutions to smaller [[instance]]s of the same problem  
such problems can generally be solved by [[iteration]], but this needs to identify and index the smaller instances at programming time  
recursion solves such recursive problems by using [[subroutine]]s that call themselves from within their own code  
  
most [[programming language]]s support recursion by allowing a function to call itself from within its own code  
moreover, some [[functional programming]] languages do not define any looping constructs, but rely solely on recursion to repeatedly call code  
  
it is proved in [[computability theory]] that these recursive-only languages are [[turing complete]]  
  
repeatedly calling a function from within itself may cause the [[call stack]] to have a size equal to the sum of the input sized of all involved calls  
hence, the importance of using optimisation techniques such as [[tail call]] on large problems [^1]  
  
an example of a recursive function on [[ocaml]]:  
```ocaml  
let is_prime n =  
   let rec check_from i =  
       i >= n ||  
           (n mod i <> 0 && check_from (i+1))  
   in check_from 2;;  
```  
  
  
[^1]: if not taken into account, it is perfectly possible to produce an stack overflow solely by recursive calls  
  
#functional_programming