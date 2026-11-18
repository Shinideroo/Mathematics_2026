### Exercise 6. Solving a System Using the Inverse
Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

> **Why this exercise:** shows the connection between inverse matrices and solving a linear system.

## Solution

The determinant is $2\cdot3-1=5\ne0$. Use the $2\times2$ inverse formula, then multiply by $b$:

$$
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},
\qquad
x=A^{-1}b=\frac15\begin{pmatrix}15-7\\-5+14\end{pmatrix}
=\begin{pmatrix}8/5\\9/5\end{pmatrix}.
$$

Left multiplication by $A^{-1}$ is valid because $A^{-1}Ax=x$. Verify in the original equation:

$$
Ax=\begin{pmatrix}16/5+9/5\\8/5+27/5\end{pmatrix}
=\begin{pmatrix}5\\7\end{pmatrix}=b.
$$
