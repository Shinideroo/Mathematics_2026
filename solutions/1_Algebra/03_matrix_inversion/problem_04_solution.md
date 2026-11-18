### Exercise 4. Gauss–Jordan
Find $A^{-1}$ using the Gauss–Jordan method for

$$
A=
\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}.
$$

Show the augmented matrix $[A\mid I]$ after successive operations and explain why obtaining $I$ on the left gives the inverse on the right.

> **Why this exercise:** introduces the Gauss–Jordan method together with its meaning, not merely as a sequence of operations.

## Solution

Apply the same elementary row operations to both sides of the augmented matrix:

$$
[A\mid I]=\begin{pmatrix}1&2&\mid&1&0\\3&5&\mid&0&1\end{pmatrix}.
$$

Use $R_2\leftarrow R_2-3R_1$, then $R_2\leftarrow-R_2$:

$$
\begin{pmatrix}1&2&\mid&1&0\\0&-1&\mid&-3&1\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&2&\mid&1&0\\0&1&\mid&3&-1\end{pmatrix}.
$$

Use $R_1\leftarrow R_1-2R_2$:

$$
[I\mid A^{-1}]=\begin{pmatrix}1&0&\mid&-5&2\\0&1&\mid&3&-1\end{pmatrix}.
$$

Thus $A^{-1}=\begin{pmatrix}-5&2\\3&-1\end{pmatrix}$. If the combined row operation matrix is $E$, the reduction says $EA=I$, and applying it to the right side gives $EI=E=A^{-1}$. This explains the method.

Check:

$$
AA^{-1}=\begin{pmatrix}-5+6&2-2\\-15+15&6-5\end{pmatrix}=I.
$$
