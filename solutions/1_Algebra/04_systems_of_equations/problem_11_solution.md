### Exercise 11. A Parameter in a System of Three Equations
Analyze the number of solutions depending on $t$:

$$
\begin{cases}
x+y+z=1, \\
x+ty+z=2, \\
x+y+tz=3.
\end{cases}
$$

Use elimination and separately analyze the parameter values for which a standard calculation step ceases to be valid.

> **Why this exercise:** develops parametric analysis while still relying only on elimination.

## Solution

Subtract the first equation from each of the other two:

$$
x+y+z=1,\qquad (t-1)y=1,\qquad (t-1)z=2.
$$

If $t\ne1$, division is valid and gives the unique solution

$$
y=\frac1{t-1},\qquad z=\frac2{t-1},\qquad
x=1-\frac3{t-1}=\frac{t-4}{t-1}.
$$

Verify using the transformed equations: $x+y+z=1$, $(t-1)y=1$, and $(t-1)z=2$. Adding the latter two equations back to the first recovers the required right sides $2$ and $3$.

At $t=1$, the second transformed equation reads $0=1$, so no solution exists. This case must be considered before division by $t-1$. There is no parameter value giving infinitely many solutions.
