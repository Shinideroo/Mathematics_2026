### Problem 9. Minimizing the Material Used for a Can
A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

> **Why this problem:** it requires independent reduction of a problem with two variables to one objective function and control of the geometric constraint.

## Solution

Let $r>0$ be the radius and $h>0$ the height, with fixed positive volume $V$. The constraint is

$$
\pi r^2h=V,\qquad h=\frac{V}{\pi r^2}.
$$

A closed cylinder has two circular ends and a curved side, so its surface area is

$$
S(r)=2\pi r^2+2\pi rh=2\pi r^2+\frac{2V}{r},
\qquad r>0.
$$

Differentiate and solve:

$$
S'(r)=4\pi r-\frac{2V}{r^2}=0
\quad\Longrightarrow\quad
r^3=\frac{V}{2\pi}.
$$

Thus

$$
r_*=\left(\frac{V}{2\pi}\right)^{1/3},
\qquad
h_*=\frac{V}{\pi r_*^2}=2r_*.
$$

For verification, $S''(r)=4\pi+4V/r^3>0$ on the domain, and $S(r)\to+\infty$ at either end. Hence the critical point is the unique global minimum.

The optimal height equals the diameter: the axial cross-section is a square. The corresponding minimum area is $6\pi(V/(2\pi))^{2/3}$.
