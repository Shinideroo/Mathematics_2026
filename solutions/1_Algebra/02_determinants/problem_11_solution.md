### Exercise 11. Shortening the Calculation with Row Operations
Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

> **Why this exercise:** develops planning instead of mechanically repeating the same procedure.

## Solution

Adding a multiple of a different row does not change the determinant. First apply $R_2\leftarrow R_2-R_1$:

$$
\begin{pmatrix}1&2&3\\0&1&1\\1&4&6\end{pmatrix}.
$$

Next apply $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}1&2&3\\0&1&1\\0&2&3\end{pmatrix}.
$$

Then apply $R_3\leftarrow R_3-2R_2$:

$$
U=\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix}.
$$

Each operation preserves the determinant. The triangular diagonal product is $1$, so the original determinant is $1$.

If desired, create zeros above the diagonal too: $R_2\leftarrow R_2-R_3$, then $R_1\leftarrow R_1-3R_3$, then $R_1\leftarrow R_1-2R_2$ produces $I$. All preserve the determinant, verifying the answer $\det I=1$ and leaving all six off-diagonal entries zero.
