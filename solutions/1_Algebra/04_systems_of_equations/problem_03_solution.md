### Exercise 3. Inconsistent System
Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

> **Why this exercise:** teaches how to recognize that a system has no solution without guessing.

## Solution

Apply $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}1&2&\mid&3\\2&4&\mid&7\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&2&\mid&3\\0&0&\mid&1\end{pmatrix}.
$$

The last row means $0x+0y=1$, which is impossible. Therefore the system has **no solution**.

This is also checked directly: twice the first equation would require $2x+4y=6$, whereas the second requires $7$. Elimination exposes that contradiction without choosing unknown values.
