### Exercise 5. A 3×3 Matrix
Use Gauss–Jordan elimination to find the inverse of

$$
A=
\begin{pmatrix}
1 & 1 & 0 \\
0 & 1 & 1 \\
1 & 0 & 1 \\
\end{pmatrix}.
$$

Check the result by multiplication.

> **Why this exercise:** provides necessary practice with the full method in a situation where the $2\times2$ formula no longer applies.

## Solution

Start with $[A\mid I]$, then use $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}1&1&0&\mid&1&0&0\\0&1&1&\mid&0&1&0\\1&0&1&\mid&0&0&1\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&1&0&\mid&1&0&0\\0&1&1&\mid&0&1&0\\0&-1&1&\mid&-1&0&1\end{pmatrix}.
$$

Use $R_3\leftarrow R_3+R_2$, then $R_3\leftarrow R_3/2$:

$$
\begin{pmatrix}1&1&0&\mid&1&0&0\\0&1&1&\mid&0&1&0\\0&0&2&\mid&-1&1&1\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&1&0&\mid&1&0&0\\0&1&1&\mid&0&1&0\\0&0&1&\mid&-\frac12&\frac12&\frac12\end{pmatrix}.
$$

Use $R_2\leftarrow R_2-R_3$, then $R_1\leftarrow R_1-R_2$:

$$
\begin{pmatrix}1&1&0&\mid&1&0&0\\0&1&0&\mid&\frac12&\frac12&-\frac12\\0&0&1&\mid&-\frac12&\frac12&\frac12\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&0&0&\mid&\frac12&-\frac12&\frac12\\0&1&0&\mid&\frac12&\frac12&-\frac12\\0&0&1&\mid&-\frac12&\frac12&\frac12\end{pmatrix}.
$$

Gauss–Jordan applies invertible row operations to turn $A$ into $I$, so the right block is

$$
A^{-1}=\frac12\begin{pmatrix}1&-1&1\\1&1&-1\\-1&1&1\end{pmatrix}.
$$

Verification:

$$
AA^{-1}=\frac12\begin{pmatrix}2&0&0\\0&2&0\\0&0&2\end{pmatrix}=I.
$$
