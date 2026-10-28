### Exercise 1. Determinant of a 2×2 Matrix
Compute

$$
\det
\begin{pmatrix}
3 & -2 \\
5 & 4 \\
\end{pmatrix},\qquad \det
\begin{pmatrix}
1 & 7 \\
2 & 14 \\
\end{pmatrix}.
$$

Which matrix is invertible? Justify your answer.

> **Why this exercise:** introduces the simplest determinant calculation and immediately connects it with invertibility.

## Solution

For a $2\times2$ matrix, the determinant is $ad-bc$. Therefore

$$
\det\begin{pmatrix}3&-2\\5&4\end{pmatrix}
=3\cdot4-(-2)\cdot5=12+10=22,
$$

$$
\det\begin{pmatrix}1&7\\2&14\end{pmatrix}
=1\cdot14-7\cdot2=0.
$$

A square matrix is invertible exactly when its determinant is nonzero, so only the first matrix is invertible.

For verification, its inverse is $\frac1{22}\begin{pmatrix}4&2\\-5&3\end{pmatrix}$: multiplying by the original matrix gives $\frac1{22}\begin{pmatrix}22&0\\0&22\end{pmatrix}=I$. In the second matrix, row two is twice row one, confirming singularity.
