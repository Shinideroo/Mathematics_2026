### Exercise 4. Plane Through Three Points
Find the equation of the plane through

$$
A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1).
$$

First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

> **Why this exercise:** connects earlier vector tools with constructing the equation of a plane.

## Solution

Construct in-plane directions:

$$
\overrightarrow{AB}=(-1,1,0),\qquad
\overrightarrow{AC}=(-1,0,1).
$$

Their cross product is

$$
n=\overrightarrow{AB}\times\overrightarrow{AC}=(1,1,1).
$$

It is nonzero, so the points determine a plane. Point-normal form at $A$ gives $(x-1)+y+z=0$, or

$$
x+y+z=1.
$$

All three points satisfy it because their coordinate sums are $1$. Also $n\cdot\overrightarrow{AB}=0$ and $n\cdot\overrightarrow{AC}=0$, verifying the normal.
