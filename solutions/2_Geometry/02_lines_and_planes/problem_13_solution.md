### Exercise 13. Closest Point on a Plane
Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

> **Why this exercise:** combines projection, distance, and the normal direction in one problem.

## Solution

Use the normal $n=(1,2,2)$ with $\|n\|^2=9$. The plane residual at $P$ is $n\cdot P-4=3-4=-1$. Hence the closest point is

$$
Q=P-\frac{-1}{9}n
=\left(\frac{28}{9},\frac29,\frac29\right).
$$

The distance is

$$
d(P,\Pi)=\frac{|-1|}{3}=\frac13.
$$

Check: $28/9+4/9+4/9=4$, so $Q$ lies on the plane; $Q-P=n/9$ is parallel to its normal, with length $3/9=1/3$. For any other plane point $X$, $X-Q$ is perpendicular to $P-Q$, so $\|P-X\|^2=\|P-Q\|^2+\|Q-X\|^2$. This proves minimality.
