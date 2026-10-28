### Exercise 10. Detecting Dependence
Without carrying out a full determinant calculation, explain why

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}=0.
$$

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

> **Why this exercise:** teaches how to recognize a zero determinant from the structure of a matrix.

## Solution

Row two is twice row one:

$$
R_2=2R_1,\qquad R_2-2R_1=0.
$$

The rows are therefore linearly dependent. Applying $R_2\leftarrow R_2-2R_1$ preserves the determinant and produces

$$
\begin{pmatrix}1&2&3\\0&0&0\\0&1&5\end{pmatrix}.
$$

A matrix with a zero row has determinant zero, so the original determinant is $0$ and the matrix is not invertible.

As a check of noninvertibility, the nonzero vector $\begin{pmatrix}7\\-5\\1\end{pmatrix}$ maps to zero: its row products are $7-10+3=0$, $14-20+6=0$, and $-5+5=0$.
