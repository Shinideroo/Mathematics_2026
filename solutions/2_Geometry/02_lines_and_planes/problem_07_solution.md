### Exercise 7. A Line Relative to a Plane
For

$$
L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,
$$

determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

> **Why this exercise:** builds a universal test for the relative position of a line and a plane.

## Solution

The direction vector is $v=(1,-1,0)$, and the plane normal is $n=(1,1,1)$. Since $n\cdot v=1-1=0$, the line direction is parallel to the plane.

The base point $(1,1,0)$ satisfies $x+y+z=2$. Therefore the whole line lies in the plane.

Verify directly for every parameter:

$$
(1+t)+(1-t)+0=2.
$$

A zero direction-normal dot product means the plane expression is constant along the line. The base-point test distinguishes containment from parallelism without intersection.
