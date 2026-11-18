### Exercise 6. Angle Between Planes
Given

$$
\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.
$$

First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

> **Why this exercise:** focuses attention on one mechanism—using normals to analyze position and angle—without also introducing the construction of the intersection line.

## Solution

The normals are $n_1=(1,1,1)$ and $n_2=(1,-1,0)$. They are not proportional, so the planes are not parallel.

The smaller angle between planes equals the smaller angle between their normal directions:

$$
\cos\theta=\frac{|n_1\cdot n_2|}{\|n_1\|\|n_2\|}
=\frac{|1-1+0|}{\sqrt3\sqrt2}=0.
$$

Thus $\theta=\pi/2=90^\circ$: the planes are perpendicular. Normals determine orientation, whereas the right-hand constants only shift the planes; therefore normals alone suffice for this angle calculation.
