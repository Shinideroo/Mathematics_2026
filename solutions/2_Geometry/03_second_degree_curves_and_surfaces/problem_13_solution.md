### Exercise 13. Intersection of a Sphere and a Plane
Given the sphere

$$
x^2+y^2+z^2=25
$$

and the plane $z=3$, find the equation of the intersection curve and its radius. Then describe what happens for $z=c$ depending on $c$.

> **Why this exercise:** connects a surface equation with the geometry of its intersection.

## Solution

Substitute $z=3$ into the sphere:

$$
x^2+y^2+9=25
\quad\Longrightarrow\quad x^2+y^2=16.
$$

The intersection is the circle $x^2+y^2=16$, $z=3$, centered at $(0,0,3)$ and of radius $4$.

For $z=c$, the equation becomes $x^2+y^2=25-c^2$:

- $|c|<5$: circle of radius $\sqrt{25-c^2}$.
- $|c|=5$: the single point $(0,0,c)$.
- $|c|>5$: no intersection.

For verification, $(4,0,3)$ satisfies $16+0+9=25$. Geometrically, the section radius obeys $r^2+c^2=5^2$, the right-triangle relation from the sphere center.
