a system of [[linear equation]]s is a collection of one or more [[linear equation]]s involving the same variables  
  
$$  
\begin{cases} a_{11}x_1+a_{12}x_2+ & \cdots & +a_{1n}x_n &= b_1 \\a_{21}x_1+a_{22}x_2+ & \cdots & +a_{2n}x_n &= b_2\\ \vdots & \vdots & \vdots & \vdots \\ a_{m1}x_1+a_{m2}x_2+ & \cdots & +a_{mn}x_n &= b_n\end{cases}  
$$  
  
a solution of the system is a list $\overbrace{s_1,\ldots ,s_n}^{\text{element in } \mathbb{R} \times \overbrace{\ldots}^n \times \mathbb{R} \\ \text{ or in } \mathbb{Z}_p}$ of numbers that makes each equation a true statement when the values $s_1,\ldots , s_n$ are substituted for $x_1, \ldots , x_n$ respectively  

in mathematics, the theory of linear systems is the basis and a fundamental part of linear algebra
  
the [[set]] of all possible solutions is called the solution set of the linear system  

we may use a [[matrix]] to represent a given linear system: 

$$\begin{pmatrix}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} \\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} \\
\vdots  & \vdots  & \ddots & \vdots  \\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} 
\end{pmatrix}$$

the augmented matrix also includes the constant terms:
$$
\left(\begin{array}{@{}cccc|c@{}}
a_{1,1} & a_{1,2} & \cdots & a_{1,n} & b_2\\
a_{2,1} & a_{2,2} & \cdots & a_{2,n} & b_2\\
\vdots  & \vdots  & \ddots & \vdots  & \vdots\\
a_{m,1} & a_{m,2} & \cdots & a_{m,n} & b_m 
\end{array}\right)
$$
in general, the behaviour of a linear system is determined by the relationship between the number of equations and the number of unknowns, in general:
- a system with fewer equations than unknowns has infinitely many solutions, but may not have any, such a system is called [[undetermined system]]
- a system with the same number of equations and unknowns has a single unique solution
- a system with more equations than unknowns has no solution, such a system is  an [[overdetermined system]]


#linear_systems 