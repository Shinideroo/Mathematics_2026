### Exercise 14. A Small Change in the Right-Hand Side
Compare the systems

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3
\end{cases}
$$

and

$$
\begin{cases}
x+y=2, \\
2x-y=1, \\
3x=3.1.
\end{cases}
$$

Check the consistency of each system and explain why a small change in one number can change the type of the system.

> **Why this exercise:** shows the difference between a consistent and an inconsistent system without introducing new theory.

## Solution

Adding the first two equations, which are common to both systems, forces $3x=3$. Hence $x=1$ and $y=1$.

In the first system, the last equation is exactly that sum. Therefore $(1,1)$ is the unique solution; substitution gives $2$, $1$, and $3$ as required.

In the second system, subtracting the sum of the first two equations from the third produces

$$
0=3.1-3=0.1.
$$

This contradiction means there is no solution. A small numerical change breaks the exact dependence of the right-hand sides while the coefficient dependence remains unchanged. Consistency requires exact agreement, so the solution type can change.
