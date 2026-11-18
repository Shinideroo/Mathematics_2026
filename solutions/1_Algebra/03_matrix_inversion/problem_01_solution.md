### Exercise 1. Definition of the Inverse
For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

check, without using a formula, whether $B=A^{-1}$. Compute $AB$ and $BA$ and relate the result to the definition of the inverse.

> **Why this exercise:** starts from the definition of the inverse through multiplication before any formulas or computational methods are introduced.

## Solution

Multiply directly, using the definition that an inverse must give the identity in both orders:

$$
AB=\begin{pmatrix}2-1&-2+2\\1-1&-1+2\end{pmatrix}=I,
\qquad
BA=\begin{pmatrix}2-1&1-1\\-2+2&-1+2\end{pmatrix}=I.
$$

Both products equal $\begin{pmatrix}1&0\\0&1\end{pmatrix}$. Hence $B=A^{-1}$; the two calculations are the required verification.
