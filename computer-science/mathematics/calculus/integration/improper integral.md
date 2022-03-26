in mathematical analysis, an improper integral is the [[limit]] of an [[integral]] as an endpoint of the [[interval]]s of the integration approaches either a specified [[real number]], $\infty$, $-\infty$,  or in some instances, as both approaches limits
specifically, an improper integral is a limit of the form:
 
 $$\lim_{b\to \infty}\int_a^bf(x)dx$$$$\lim_{a\to \infty}\int_a^bf(x)dx$$
 
  $$\lim_{c\to b^-}\int_a^cf(x)dx$$  $$\lim_{c\to a^+}\int_c^bf(x)dx$$
  
  by abuse of notation, improper integrals are often written symbolically just like standard definite integrals, perhaps with infinity among the limits of integration
  
  when the definite integral exists, this ambiguity is resolved as both the proper and improper integral will coincide in value
  
  often one is able to compute values for improper integrals, even when the [[mathematical function]] is not a [[riemann integrable function]], because of a singularity in the function or because one of the bounds of integration is infinite
  
  improper integrals can be classified on:
  - first specie integral: $(a,b)$ not bounded, $f$ bounded on $(a,b)$
	 -  let $f:(-\infty , b]\to \mathbb{R}$ [[riemann integrable function]] on $[m,b]$, $\forall m \leq b$, we define: $$\int_{-\infty}^b f(x)dx=\lim_{m\to-\infty}\int_m^b f(x)dx$$ if the [[limit]] exists 
	 -  if the limit is finite, the  [[integral]] is said to be convergent[^1]
	 -  in a similar manner, if $f:(-\infty]\to \mathbb{R}$ [[riemann integrable function]] on $[a,M]$, $\forall M \leq a$, we define: $$\int_{a}^{-\infty} f(x)dx=\lim_{M\to \infty}\int_a^M f(x)dx$$ if the limit exists 
	 -  finally, we define $$\int_{-\infty}^{\infty}f(x)dx=\int_{-\infty}^{a}f(x)dx+\int_{a}^{\infty}f(x)dx$$
	 -  if the integral $\int_{-\infty}^{\infty}f(x)dx$ exists, its value is not dependent of $a\in \mathbb{R}$
  

  - second specie integral $(a,b)$ bounded, $f$ not bounded on $(a,b)$
	  - let $f:[a,b)\to \mathbb{R}$ is such that $\lim_{t\to a^+}f(x)= \pm \infty$ and $f$ is [[riemann integrable function]] on $[t,b], \forall t\in[a,b)$, then we define: $$\int_a^bf(x)dx=\lim_{t\to a^+}\int_t^bf(x)dx$$ if the [[limit]] exists 
	  - in a similar manner, if $f:[a,b)\to \mathbb{R}$ is such that $\lim_{t\to b^-}f(x)= \pm \infty$ and $f$ is [[riemann integrable function]] on $[a,t], \forall t\in[a,b)$, then we define: $$\int_a^bf(x)dx=\lim_{t\to b^-}\int_a^tf(x)dx$$ if the [[limit]] exists 
	  - if the limit is finite, we say that the integral is convergent [^1]
	  - if $\lim_{x\to c}f(x)=\pm \infty$, with $c\in (a,b)$ and it exists $\int_a^cf(x)dx$ and $\int_c^bf(x)dx$ then we define : $$\int_a^bf(x)dx=\int_a^cf(x)dx+\int_c^bf(x)dx$$
  - third specie integral: $(a,b)$, not bounded, $f$ not bounded on $(a,b)$



[^1]:[[convergence of the integral]]


#integrals 