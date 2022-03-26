in computer science, the computational complexity, or simply complexity of an [[algorithm]] is the amount of resources required to run it
there tends to be a particular focus on either time or memory complexity
the complexity of a computational problem is the complexity of the best algorithms that solve that specific problem

the study of the complexity of explicitly given algorithms is called [[analysis of algorithms]], while the study of the complexity of problems is called computational complexity theory
both are closely related, as the complexity of an algorithm is always an [[upper bound]] on the complexity of the problem solved by this algorithm

as the amount of resources required to run an algorithm varies with the size of the input, the complexity tends to be represented as a [[mathematical function]] $n\rightarrow f(n)$ where $n$ is the side of input and $f(n)$ either the [[worst-case complexity]] or [[average-case complexity]]

- time analysis: the most common resource considered, the usual units of time are not used in complexity theory because they are too dependent on the specifics of the [[hardware]] they are executed, rather, the number of elementary operations that are executed during the computation, the steps
- space analysis: another common resource considered is the [[computer memory]] needed for the algorithm to be executed

 it is generally difficult to compute precisely worst or average case complexities, also, for small values of $n$, resource use tends not to be critical
 thus, the focus is generally put on the behaviour of the complexity for large $n$, that is, n its [[asymptotic behaviour]], when $n$ tends to infinity
 this is generally expressed using [[asymptotic notation]]

the evaluation of the complexity relies on the choice of a [[model of computation]], consisting in defining the basic operations that are done in an unit of time

#computational_complexity