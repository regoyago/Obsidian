in calculus, a method called implicit differentiation makes use of the [[chain rule]] to differentiate  implicitly defined [[mathematical function]]s

to differentiate an implicit function $y(x)$, defined by an equation $F(x,y)=0$, it is not generally possible t solve it explicitly for $y$ and then differentiate
instead, one can totally differentiate $F(x,y)=0$ with respect to $x$ and to $y$ and then solve the resulting [[linear equation]]for $\frac{dy}{dx}$ to explicitly get the [[derivative]] in terms of $x$ and $y$

even when it is possible to explicitly solve the original equation, the formula resulting from total differentiation, is, in general, much simpler and easier to use 

general formula for derivative of implicit function:
if $F(x,y)=0$, the [[derivative]] of the implicit function $y(x)$ is given by:
$$\frac{dy}{dx}=-\frac{\frac{\delta F}{\delta x}}{\frac{\delta R}{\delta y}}=-\frac{F_x}{F_y}$$

where $F_x$ and $F_y$ indicate the [[partial derivative]]s of $F$ with respect to $x$ and to $y$

the above formula comes from using the generalized [[chain rule]] to obtain the total derivative, with respect to $x$ of both sides of $F(x,y)=0$

$$\frac{\delta F}{\delta x}\frac{dx}{dx}+\frac{\delta F}{\delta y}\frac{dy}{dx}=0$$
hence:
$$\frac{\delta F}{\delta x}+\frac{\delta F}{\delta y}\frac{dy}{dx}=0$$
which, when solved for $\frac{dy}{dx}$ gives the expression above

#derivatives