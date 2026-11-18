### Problem 5. Distance from Velocity
The velocity of a car during the first five seconds is described by the function

$$
v(t)=4t+2\quad [\mathrm{m/s}].
$$

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

> **Why this problem:** it connects the integral with accumulation and distinguishes displacement from the actual distance traveled.

## Solution

The velocity is positive on $[0,5]$, so distance equals displacement:

$$
D=\int_0^5(4t+2)\,dt
=[2t^2+2t]_0^5=50+10=60\ \mathrm m.
$$

Because velocity is the derivative of position, the fundamental theorem gives $\int_0^5v(t)\,dt=s(5)-s(0)$. Integration sums each short-time change in position.

If velocity took negative values, displacement would still be $\int v(t)\,dt$, but total distance would be $\int|v(t)|\,dt$, splitting at sign changes.

Verification: the graph of velocity is a straight line from $2$ to $22$ m/s. Its trapezoid area is $(2+22)5/2=60$ m.
