### Exercise 1. Line Through Two Points
Find the equation of the line through $A=(1,2)$ and $B=(4,-1)$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

> **Why this exercise:** teaches how to move between equivalent descriptions of a line and connect them with the appropriate vectors.

## Solution

A direction is $B-A=(3,-3)$, which can be rescaled to $v=(1,-1)$. Thus the parametric form is

$$
(x,y)=(1,2)+t(1,-1),\qquad t\in\mathbb R.
$$

A perpendicular normal is $n=(1,1)$ because $n\cdot v=0$. The point-normal equation is $(x-1)+(y-2)=0$, giving general form

$$
x+y-3=0.
$$

Check: at $A$, $1+2-3=0$; at $B$, $4-1-3=0$. The parametric form reaches them at $t=0$ and $t=3$, respectively.
