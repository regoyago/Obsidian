in mathematics, a riemann sum is a certain kind of approximation of an integral by a finite sum

the sum is calculated by partitioning the region into shapes that together form a region that is similar to the region being measured, then calculating the area for each of these shapes. and finally adding all of these small areas together
this approach can be used to find a numerical approximation for a [[integral]] even if the [[fundamental theorem of calculus]] does not make it easy to find a closed form solution

because the region filled by the small shapes is usually not exactly the same shape as the region being measured, the riemann sum will differ from the area being measured. 
this error can be reduced by dividing the region more finally, using smaller and smaller shapes. as the shapes get smaller, the sum approaches the [[riemann integral]]

let $f:[a,b]\to \mathbb{R}$ be a function defined on a closed [[interval]] $[a,b]$ of the [[real number]]s and
$$P=\{[x_0,x_1],[x_1,x_2],\ldots ,[x_{n-1},x_n]\}$$
be a [[partition]] of $I$ where
$$a=x_0<x_1< \ldots <x_n=b$$

a riemann sum $S$ of $f$ over $I$ with partition $P$ is defined as 

$$S=\sum_{i=1}^nf(x_i^*)\Delta x_i$$

where $\Delta x_i = x_i-x_{i-1}$ and $x^* \in  [x_{i-1},x_i]$

one might produce different riemann sums depending on which $x^*_i$'s are chosen, in the and this will not mater, if the function is riemann integrable, when the difference or width of the summands $\Delta x_i$ approaches zero

specific riemann sums:
- left riemann sum: $x^*_i=x_{i-1}$
- right riemann sum: $x^*_i=x_{i}$
- middle riemann sum: $x^*_i=\frac{x_{i-1}+x_i}{2}$
- upper riemann sum: $f(x^*_i)=sup f([x_{i-1},x_i])$[^1]
- lower riemann sum: $f(x^*_i)=inf f([x_{i-1},x_i])$[^2]


[^1]:that is, taking the partition as a [[patially ordered set (poset)]], its supremum (biggest)
[^2]:that is, taking the partition as a [[patially ordered set (poset)]], its infimum (smallest)

#integrals
#numeric_integration
#approximation_method 