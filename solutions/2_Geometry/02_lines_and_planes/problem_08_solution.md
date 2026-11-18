### Exercise 8. Intersection Point of a Line and a Plane
Find the intersection point of

$$
(x,y,z)=(1,0,2)+t(1,2,-1)
$$

with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

> **Why this exercise:** practices the most important computational case of the line–plane relationship.

## Solution

Substitute the line coordinates $x=1+t$, $y=2t$, $z=2-t$ into the plane:

$$
(1+t)+2t+(2-t)=4
\quad\Longrightarrow\quad 3+2t=4.
$$

Hence $t=1/2$, giving the unique intersection

$$
\left(\frac32,1,\frac32\right).
$$

Check: substituting $t=1/2$ into the line gives this point, and its coordinate sum is $3/2+1+3/2=4$. The coefficient $2$ is the nonzero dot product of the line direction with the plane normal, guaranteeing uniqueness.
