### Exercise 11. Plane Containing a Line and a Point
Find the equation of the plane containing

$$
(x,y,z)=(1,0,2)+t(1,1,-1)
$$

and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

> **Why this exercise:** requires independently constructing two linearly independent directions in the plane.

## Solution

Let the line's base point be $A=(1,0,2)$. Two in-plane directions are

$$
v=(1,1,-1),\qquad P-A=(-1,2,-1).
$$

They are independent, and their cross product is

$$
n=v\times(P-A)=(1,2,3).
$$

Point-normal form gives

$$
(x-1)+2y+3(z-2)=0
\quad\Longrightarrow\quad x+2y+3z=7.
$$

Check $P$: $0+4+3=7$. Check the entire line:

$$
(1+t)+2t+3(2-t)=7
$$

for every $t$. These substitutions verify both required containment conditions.
