### Exercise 10. A Polynomial Through Three Points
Find a polynomial $p(x)=ax^2+bx+c$ whose graph passes through $(0,1)$, $(1,3)$, and $(2,9)$. Reduce the problem to a system of equations and check the result by substituting all three points.

> **Why this exercise:** shows that finding unknown coefficients can be reduced to solving a linear system.

## Solution

Substitute each point into $p(x)=ax^2+bx+c$:

$$
c=1,\qquad a+b+c=3,\qquad 4a+2b+c=9.
$$

After using $c=1$, this becomes $a+b=2$ and $4a+2b=8$. Subtracting twice the first from the second gives $2a=4$, so $a=2$, $b=0$, and $c=1$. Therefore

$$
p(x)=2x^2+1.
$$

The coefficient equations are linear even though the polynomial is quadratic in its argument. Verification at all points gives $p(0)=1$, $p(1)=3$, and $p(2)=9$.
