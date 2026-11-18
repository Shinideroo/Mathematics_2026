### Exercise 4. Infinitely Many Solutions
Solve

$$
\begin{cases}
x+y+z=2, \\
2x+2y+2z=4, \\
x-y+z=0.
\end{cases}
$$

Give the solution in parametric form, identify a free variable, and for one chosen parameter value check that the resulting point really satisfies the system.

> **Why this exercise:** shows the case of multiple solutions and teaches a simple parametric description.

## Solution

Use $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}1&1&1&\mid&2\\0&0&0&\mid&0\\0&-2&0&\mid&-2\end{pmatrix}.
$$

The independent equations are $y=1$ and $x+z=1$. Take the free variable $z=s$, $s\in\mathbb R$. All solutions are

$$
(x,y,z)=(1-s,1,s).
$$

There are infinitely many because $s$ is unrestricted. Substitution verifies the family: the three left sides become $2$, $4$, and $0$, respectively. In particular, $s=0$ gives $(1,1,0)$, which satisfies every original equation.
