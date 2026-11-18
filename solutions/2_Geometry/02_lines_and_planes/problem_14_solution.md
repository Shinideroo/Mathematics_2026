### Exercise 14. Contrast: Intersection and Parallelism
From the point $P=(0,0,1)$, two lines are drawn with direction vectors

$$
v_1=(2,1,-1),\qquad v_2=(2,1,0).
$$

For each line, analyze its position relative to the plane $z=0$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

> **Why this exercise:** compares two very similar data sets that lead to different outcomes and forces recognition of the geometric condition before calculation.

## Solution

The plane $z=0$ has normal $n=(0,0,1)$.

For direction $v_1=(2,1,-1)$, $n\cdot v_1=-1\ne0$. The line is $(2t,t,1-t)$; setting $z=0$ gives $t=1$ and intersection $(2,1,0)$. This point satisfies both the line and plane.

For $v_2=(2,1,0)$, $n\cdot v_2=0$. Its line has constant height $z=1$, so it is parallel to the plane with no common point. No equation solving is necessary: the direction has zero vertical component and the base point is outside the plane.
