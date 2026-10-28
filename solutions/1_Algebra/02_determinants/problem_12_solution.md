### Exercise 12. A Parameter Revealed by a Row Operation
For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

> **Why this exercise:** combines a parameter, row operations, and recognition of dependence in one short argument.

## Solution

Before computing the determinant, apply the specified operation $R_2\leftarrow R_2-2R_1$. It preserves the determinant:

$$
M(t)=\begin{pmatrix}1&2&3\\0&0&t-6\\0&1&1\end{pmatrix}.
$$

Expand along the first column and evaluate the remaining $2\times2$ determinant:

$$
\det A(t)=1\det\begin{pmatrix}0&t-6\\1&1\end{pmatrix}
=-(t-6)=6-t.
$$

Thus the matrix is not invertible exactly when $t=6$.

At $t=6$, the transformed second row is zero. In the original matrix the special relationship is $R_2=2R_1$, verifying row dependence. For every $t\ne6$, the determinant is nonzero.
