### Exercise 12. Recognizing a Surface from Cross-Sections
A certain surface has the following properties:
- the cross-section $z=0$ is a point,
- for $z>0$, the cross-sections $z=\mathrm{const}$ are circles with increasing radius,
- vertical cross-sections through the $Oz$ axis are parabolas.

Propose a simple equation for such a surface and justify your choice.

> **Why this exercise:** reverses the usual reasoning: from geometry to an equation.

## Solution

One simple possible equation is

$$
z=x^2+y^2.
$$

At $z=0$, the equation forces $x=y=0$, giving a point. At $z=c>0$, it gives a circle $x^2+y^2=c$ of radius $\sqrt c$, which increases with $c$.

For any vertical plane through $Oz$, write $(x,y)=(r\cos\theta,r\sin\theta)$ with fixed $\theta$ and signed coordinate $r$. Then $z=r^2$, a parabola in that plane.

All the stated properties are therefore satisfied. They do not specify a unique scale: $z=a(x^2+y^2)$ for any $a>0$ also works. The displayed equation is a valid proposal, not a claim of uniqueness.
