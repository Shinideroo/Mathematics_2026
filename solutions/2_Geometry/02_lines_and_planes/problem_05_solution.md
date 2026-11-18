### Exercise 5. Relative Position of Two Lines
Analyze the position of

$$
L_1:(x,y,z)=(1,1,0)+t(1,2,1),
$$

$$
L_2:(x,y,z)=(2,0,1)+s(0,1,-1).
$$

If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

> **Why this exercise:** teaches how to distinguish qualitatively different relationships between lines in space.

## Solution

The direction vectors $(1,2,1)$ and $(0,1,-1)$ are not proportional, so the lines are not parallel. For an intersection, equate coordinates:

$$
1+t=2,\qquad 1+2t=s,\qquad t=1-s.
$$

The first equation gives $t=1$, and the second then gives $s=3$. The third would require $1=-2$, a contradiction. Equivalently, the candidate points are $(2,3,1)$ on $L_1$ and $(2,3,-2)$ on $L_2$, which differ.

The lines neither intersect nor are parallel, so they are **skew**.
