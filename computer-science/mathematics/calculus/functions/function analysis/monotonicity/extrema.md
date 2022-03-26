in mathematical analysis, the maxima and minima of a [[mathematical function]] are the largest and smallest values of a function either within a given [[range]] (local extrema) or on the entire [[domain]] (absolute extrema)

as defined, the maximum and minimum of a [[set]] are the greatest and least elements in the set respectively.
unbounded infinite sets have no minimum or maximum

for a real-valued [[mathematical function]] $f$ defined on a domain $X$
- $f$ has a global or absolute maximum point at $x_0$ if $f(x_0)\leq f(x) \forall x \in X$, it is usually denoted as $max(f(x))$
- $f$ has a global or absolute minimum point at $x_0$ if $f(x_0)\geq f(x) \forall x \in X$, it is usually denoted as $min(f(x))$

the local cases are defined similarly, but only taking into account the values that the function takes on the specified range 

in order to find extrema, the definition of [[derivative]] or [[derivative at a point]] is used, since, as stated, a derivative at a point studies the rate of change, which can  be interpreted as the immediate slope of the function at a given point or as a whole [[monotonic function]]
an extrema point must be the point in which, by the right and by its left, the function has opposite slopes, thus, its [[one-sided derivative]]s have opposite signs
moreover, for this to be true, the exact point at which the function has its extrema, must have $0$ as slope, since it is not increasing nor decreasing
thus, we can affirm that if we want to find extrema on a function[^1], we need to find all points in which its [[derivative]] is $0$:
formally:
- let $f:(a,b)\to \mattbb{R}$ a [[differentiable function]] at $x_0\in (a,b)$, if $f$ has a relative extrema at $x_0$, then $f'(x_0)=0$

in order to know whether the obtained extrema is a maximum or a minimum:
- first derivative test[^2] : let $f:[a,b]\to \mathbb{R}$ be a [[continuous function]], $x_0\in (a,b)$ and let $r>0$ such that $f$ is a [[differentiable function]] on $(x_0-r,x_0)\cup (x_0,x_0+r)$
	- if $f'(x)<0, \ \ \forall x\in (x_0-r,x_0)$ and $f'(x) >0, \ \ \forall x\in (x_0,x_0+r)$, then $f$ has a relative minimum at $x_0$
	- if $f'(x)>0, \ \ \forall x\in (x_0-r,x_0)$ and $f'(x) <0, \ \ \forall x\in (x_0,x_0+r)$, then $f$ has a relative maximum at $x_0$


-  second derivative test[^3] : let $f:(a,b)\to \mathbb{R}$ with a second order [[derivative]] which is a [[continuous function]] on $(a,b)$, let $x_0 \in (a,b)$ such that $f'(x_0)=0$ then
	-  if $f''(x_0)<0$ then $f$ has a relative maximum at $x_0$
	-  	if $f''(x_0)<0$ then $f$ has a relative maximum at $x_0$


[^1]: take into account that the given function must be a [[differentiable function]] in order to be able to differentiate
[^2]:this method just analyzes the sign of the [[one-sided derivative]]s to see whether the function was previously and will continue to be increasing or decreasing
[^3]: this method applies the concept of  [[inflexion]] to the study of extrema

#function_analysis 
#derivatives 