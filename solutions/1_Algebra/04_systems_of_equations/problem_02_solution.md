### Exercise 2. Gaussian Elimination — One Solution
Solve using Gaussian elimination:

$$
\begin{cases}
x+y+z=6, \\
2x-y+z=3, \\
x+2y-z=2.
\end{cases}
$$

After solving, substitute the result into all equations and check consistency.

> **Why this exercise:** introduces the basic method for solving a system and builds the habit of checking the result.

## Solution

Begin with the augmented matrix and use $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}1&1&1&\mid&6\\2&-1&1&\mid&3\\1&2&-1&\mid&2\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&1&1&\mid&6\\0&-3&-1&\mid&-9\\0&1&-2&\mid&-4\end{pmatrix}.
$$

Swap rows two and three, then use $R_3\leftarrow R_3+3R_2$:

$$
\begin{pmatrix}1&1&1&\mid&6\\0&1&-2&\mid&-4\\0&0&-7&\mid&-21\end{pmatrix}.
$$

Row operations preserve the solution set. Back substitution gives $z=3$, $y=-4+2z=2$, and $x=6-y-z=1$. Thus $(x,y,z)=(1,2,3)$ is the unique solution, since each variable has a pivot.

Verify all equations:

$$
1+2+3=6,\qquad 2-2+3=3,\qquad 1+4-3=2.
$$
