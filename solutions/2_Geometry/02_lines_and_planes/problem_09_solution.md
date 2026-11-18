### Exercise 9. Distances
Compute:

1. the distance from $P=(2,3)$ to the line $3x+4y-10=0$,
2. the distance from $Q=(2,-1,3)$ to the plane $2x-2y+z-4=0$.

Compare the two formulas and explain their common connection with the normal direction.

> **Why this exercise:** organizes two similar formulas through one geometric idea.

## Solution

Distance to $n\cdot x+d=0$ is the absolute residual divided by $\|n\|$.

1. For the line, $n=(3,4)$:

$$
d(P,L)=\frac{|3(2)+4(3)-10|}{\sqrt{3^2+4^2}}=\frac85.
$$

2. For the plane, $n=(2,-2,1)$:

$$
d(Q,\Pi)=\frac{|2(2)-2(-1)+3-4|}{\sqrt{4+4+1}}=\frac53.
$$

Both formulas measure the component of displacement in the unit normal direction. To check, the perpendicular feet are

$$
P-\frac8{25}(3,4)=\left(\frac{26}{25},\frac{43}{25}\right),
\quad
Q-\frac59(2,-2,1)=\left(\frac89,\frac19,\frac{22}{9}\right).
$$

They satisfy their respective equations, and the lengths of the subtracted normal vectors are $8/5$ and $5/3$.
