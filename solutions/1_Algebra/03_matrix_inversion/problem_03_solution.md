### Exercise 3. When Does the Inverse Not Exist?
For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

> **Why this exercise:** connects two signs of noninvertibility instead of treating them as unrelated facts.

## Solution

The determinant is

$$
\det A=2\cdot2-4\cdot1=0,
$$

so the determinant criterion shows that $A$ is not invertible.

Independently, $R_1=2R_2$, so its rows are linearly dependent. Every output $Ax$ therefore has first component twice its second; the map cannot produce every vector in $\mathbb R^2$ and cannot have an inverse.

For verification, the nonzero vector $\begin{pmatrix}-2\\1\end{pmatrix}$ satisfies $A\begin{pmatrix}-2\\1\end{pmatrix}=0$. An invertible matrix cannot send a nonzero vector to zero.
