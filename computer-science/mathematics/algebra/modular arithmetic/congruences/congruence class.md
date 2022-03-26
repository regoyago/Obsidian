[[congruence]] modulo $n$ is an [[equivalence relation]] on the [[set]] $\mathbb{Z}$ and the [[equivalence class]] of the [[integer number]] $a$, denoted by $\bar a_n$ is the [[set]] ${\ldots ,a-2n,a-n,a,a+n,\ldots}$  
this set, consisting of all the integers congruent to $a$ [[modulo]] $n$ is the congruence class, residue class or simply, residue of the integer  
  
properties:  
given $m>1$ and $a,b,e,f$ integers satisfying:  $$a\equiv_m b$ \text{ and } $e\equiv_m f$$
then, it is true that:  
$$a+e\equiv_m b+f \text{ and } a-e\equiv_m b.f$$  
  
proof:  $$a\equiv_m b \implies m|a-b\implies a-b=k.m \text{ for } K\in \mathbb{Z} *$$$$e\equiv_m f \implies m|e-f\implies e-f=k'.m \text{ for } K\in \mathbb{Z} **$$
$ae-bf=ae-be+be-bf= e(a-b)+b(e-f)\overbrace{=}^{*,**}ekm+bk'm=$  
$m(ek+bk')\implies m|ae-bf\implies ae \equiv_m bf$  
  
#congruence