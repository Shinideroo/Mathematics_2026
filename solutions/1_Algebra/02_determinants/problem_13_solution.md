### Exercise 13. Determinant by Elimination
Compute the determinant

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}
$$

using elimination. Record the effect of every row operation used on the value of the determinant.

> **Why this exercise:** reinforces organizing a determinant calculation through row operations without introducing an unnecessary second procedure.

## Solution

Interpret the request as computing $\det A$ for the displayed matrix. Use row replacements, each of which preserves the determinant.

First, $R_2\leftarrow R_2-2R_1$ gives

$$
A_1=\begin{pmatrix}1&2&3\\0&1&1\\1&0&2\end{pmatrix},
\qquad \det A_1=\det A.
$$

Next, $R_3\leftarrow R_3-R_1$ gives

$$
A_2=\begin{pmatrix}1&2&3\\0&1&1\\0&-2&-1\end{pmatrix},
\qquad \det A_2=\det A_1.
$$

Finally, $R_3\leftarrow R_3+2R_2$ gives

$$
U=\begin{pmatrix}1&2&3\\0&1&1\\0&0&1\end{pmatrix},
\qquad \det U=\det A_2.
$$

There were no row swaps or scalings, so

$$
\det A=\det U=1\cdot1\cdot1=1.
$$

For verification of the elimination, its third-row calculation is $(1,0,2)-(1,2,3)+2(0,1,1)=(0,0,1)$, and the inverse row replacements recover the original matrix.
