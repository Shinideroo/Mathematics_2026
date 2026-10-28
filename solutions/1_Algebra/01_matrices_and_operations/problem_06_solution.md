### Exercise 6. Transpose
For

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
4 & 5 & 6 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix}
$$

compute $A^T$, $B^T$, and $AB$. Then verify in this example that

$$
(AB)^T=B^TA^T.
$$

> **Why this exercise:** teaches transposition and an important property that reverses the order of factors.

## Solution

Transposition exchanges rows and columns:

$$
A^T=\begin{pmatrix}1&4\\2&5\\3&6\end{pmatrix},
\qquad B^T=\begin{pmatrix}1&2&-1\\0&1&3\end{pmatrix}.
$$

Multiplication gives

$$
AB=\begin{pmatrix}1+4-3&0+2+9\\4+10-6&0+5+18\end{pmatrix}
=\begin{pmatrix}2&11\\8&23\end{pmatrix}.
$$

Compute the reversed product of the transposes:

$$
B^TA^T=\begin{pmatrix}1+4-3&4+10-6\\0+2+9&0+5+18\end{pmatrix}
=\begin{pmatrix}2&8\\11&23\end{pmatrix}=(AB)^T.
$$

This verifies the identity. The factor order reverses because the columns of the original product become rows after transposition.
