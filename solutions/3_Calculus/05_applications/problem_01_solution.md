### Problem 1. Motion — from Position to Velocity
The position of a point is described by

$$
s(t)=t^3-6t^2+9t+2,\qquad t\ge0.
$$

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

> **Why this problem:** it shows the derivative as a real rate of change and requires interpretation of the sign of the derivative in the context of motion.

## Solution

Velocity and acceleration are successive time derivatives of position:

$$
v(t)=s'(t)=3t^2-12t+9=3(t-1)(t-3),
\qquad
a(t)=v'(t)=6t-12.
$$

The point stops when $v(t)=0$, at $t=1$ and $t=3$.

For $0\le t<1$, both factors of the velocity are negative, so the velocity is positive. For $1<t<3$ it is negative; for $t>3$ it is positive. Thus the point moves in the positive direction on $[0,1)$ and $(3,\infty)$, and in the negative direction on $(1,3)$.

Check with representative times: $v(0)=9>0$, $v(2)=-3<0$, and $v(4)=9>0$. The positions at the stops are $s(1)=6$ and $s(3)=2$, consistent with backward motion between them.
