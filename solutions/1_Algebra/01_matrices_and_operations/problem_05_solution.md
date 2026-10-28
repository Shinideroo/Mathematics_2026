### Exercise 5. Matrix Times Vector
Let

$$
A=
\begin{pmatrix}
2 & -1 \\
1 & 3 \\
\end{pmatrix},\qquad x=
\begin{pmatrix}
4 \\
2 \\
\end{pmatrix}.
$$

Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

> **Why this exercise:** shows that multiplying a matrix by a vector can be understood as a linear combination of the matrix columns.

## Solution

Take row-by-column dot products:

$$
Ax=\begin{pmatrix}2\cdot4-1\cdot2\\1\cdot4+3\cdot2\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}.
$$

The entries of $x$ also give the coefficients of the columns:

$$
4\begin{pmatrix}2\\1\end{pmatrix}
+2\begin{pmatrix}-1\\3\end{pmatrix}
=\begin{pmatrix}8\\4\end{pmatrix}+\begin{pmatrix}-2\\6\end{pmatrix}
=\begin{pmatrix}6\\10\end{pmatrix}.
$$

Agreement of these two calculations verifies the column interpretation of $Ax$.
