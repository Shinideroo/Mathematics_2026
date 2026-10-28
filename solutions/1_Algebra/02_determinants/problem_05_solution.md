### Exercise 5. Row Operations
For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 1 & 0 \\
-1 & 4 & 2 \\
\end{pmatrix}
$$

find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

> **Why this exercise:** connects determinants with row operations and requires conscious tracking of every step.

## Solution

Adding a multiple of one row to another leaves the determinant unchanged. First use $R_2\leftarrow R_2-2R_1$:

$$
A_1=\begin{pmatrix}1&2&3\\0&-3&-6\\-1&4&2\end{pmatrix},
\qquad \det A_1=\det A.
$$

Next use $R_3\leftarrow R_3+R_1$:

$$
A_2=\begin{pmatrix}1&2&3\\0&-3&-6\\0&6&5\end{pmatrix},
\qquad \det A_2=\det A_1.
$$

Finally use $R_3\leftarrow R_3+2R_2$:

$$
U=\begin{pmatrix}1&2&3\\0&-3&-6\\0&0&-7\end{pmatrix},
\qquad \det U=\det A_2.
$$

No swaps or row scalings occurred. Thus the triangular rule gives

$$
\det A=1(-3)(-7)=21.
$$

As an arithmetic check, first-row expansion of the original gives $1(2)-2(4)+3(9)=2-8+27=21$.
