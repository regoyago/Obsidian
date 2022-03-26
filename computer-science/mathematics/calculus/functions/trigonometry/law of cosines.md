in [[trigonometry]], the law of cosines, cosine law, or al-Kashi's theorem relates the lengths of the sides of a [[triangle]] to the [[cosine]] of its angles , according to the law:
$$c^2= a^2 +b^2 - 2ab cos\gamma$$

where $\gamma$ denotes the angle contained between sides of length $a$ and $b$ and opposite the side of length $c$

the law of cosines generalizes the [[pythagorean theorem]], which holds true only for [[right triangle]]:
- if the given angle $\gamma$ is a right angle, then $cos \gamma = 0$, thus the law of cosines reduces to the pythagorean theorem:
$c^2= a^2 + b^2$

the law of cosines is useful for computing the third side of a triangle when two sides and their enclosed angle are known, and in computing the angles of a triangle if all three sides are known


- Proof by distance formula:
considering a triangle with sides of length $a,b,c$, where $\theta$ is the measurement of the angle opposite the side of length $c$
this triangle can be placed on the [[cartesian coordinate system]] aligned with edge $a$ with origin at $C$ as such: 
![[law of cosines I.png]]
$$A=(bcos \theta, b sin \theta), B=(a,0), C=(0,0)$$  

by the [[distance formula]]:
$$c=\sqrt{(a-b cos \theta)^2+(0-b sin\theta)^2}$$
squaring both sides and simplifying:
$$c^2=(a-bcos\theta)^2+(-bsin\theta)^2$$
$$c^2=a^2 -2abcos\theta + b^2cos^2\theta +b^2 sin^2 \theta$$
$$c^2 = a^2+b^2(sin ^2\theta + cos^2 \theta)- 2abcos\theta$$
$$c^2= a^2 + b^2 - 2abcos\theta$$
an advantage of this proof is that it does not require the consideration of different cases for when the triangle is acute, right or obtuse

#trigonometry 