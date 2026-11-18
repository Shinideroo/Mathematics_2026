### Exercise 10. Projection of a Point onto a Plane
Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

> **Why this exercise:** combines the normal, intersection, and distance into the construction of a projection and reflection.

## Solution

The normal is $n=(1,1,1)$ and $n\cdot P-3=6-3=3$. Subtract the normal component to obtain the projection:

$$
Q=P-\frac{n\cdot P-3}{\|n\|^2}n
=(2,1,3)-(1,1,1)=(1,0,2).
$$

The reflection is twice the projection minus the original point:

$$
P'=2Q-P=(0,-1,1).
$$

Check: $Q$ has coordinate sum $3$, and $P-Q=(1,1,1)$ is normal to the plane. The midpoint $(P+P')/2=(1,0,2)=Q$ lies on the plane. The two equal opposite normal displacements verify the reflection.
