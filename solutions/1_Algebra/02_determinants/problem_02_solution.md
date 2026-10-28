### Exercise 2. Determinant of a 3×3 Matrix
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

> **Why this exercise:** teaches a basic method for $3\times3$ matrices and builds the habit of checking the result without adding a second full solution.

## Solution

Sarrus' rule for a $3\times3$ matrix adds the three downward diagonal products and subtracts the three upward diagonal products:

$$
\det A=
(1\cdot3\cdot5+2\cdot4\cdot2+(-1)\cdot0\cdot1)
-\bigl((-1)\cdot3\cdot2+2\cdot0\cdot5+1\cdot4\cdot1\bigr)
=31-(-2)=33.
$$

For a short check, replace $R_3$ by $R_3-2R_1$, which preserves the determinant:

$$
\det A=\det\begin{pmatrix}1&2&-1\\0&3&4\\0&-3&7\end{pmatrix}
=1\bigl(3\cdot7-4(-3)\bigr)=33.
$$

Expansion down the first column confirms the result.
