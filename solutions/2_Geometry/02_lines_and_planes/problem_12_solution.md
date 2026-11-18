### Exercise 12. Intersection Line of Two Planes
Find a parametric equation of the line that is the intersection of

$$
x+y+z=3,\qquad x-y+z=1.
$$

Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

> **Why this exercise:** shows the equivalence of the algebraic and geometric approaches to constructing an intersection line.

## Solution

Subtract the plane equations to obtain $2y=2$, so $y=1$. The first then gives $x+z=2$. Let $z=t$:

$$
(x,y,z)=(2,1,0)+t(-1,0,1),\qquad t\in\mathbb R.
$$

This gives direction $v=(-1,0,1)$. Independently, the normals have cross product

$$
(1,1,1)\times(1,-1,1)=(2,0,-2)=-2v.
$$

Nonzero scalar multiples describe the same line direction, so the methods agree. Substitution gives $(2-t)+1+t=3$ and $(2-t)-1+t=1$ for every $t$, checking the full intersection line.
