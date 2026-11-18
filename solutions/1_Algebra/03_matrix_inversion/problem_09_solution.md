### Exercise 9. Matrix Equation
Given

$$
A=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
3 & 1 \\
2 & 4 \\
\end{pmatrix}.
$$

Solve the equation $AX=B$ for $X$. Before calculating, decide on which side of the equation $A^{-1}$ must be used. Then check the result by computing $AX$.

> **Why this exercise:** teaches that order matters in matrix equations and must guide the solution.

## Solution

Multiply on the left, because $A$ is on the left of $X$:

$$
A^{-1}AX=A^{-1}B,\qquad X=A^{-1}B.
$$

The determinant is $1$, and

$$
A^{-1}=\begin{pmatrix}1&-2\\0&1\end{pmatrix},
\qquad
X=\begin{pmatrix}3-4&1-8\\2&4\end{pmatrix}
=\begin{pmatrix}-1&-7\\2&4\end{pmatrix}.
$$

Check:

$$
AX=\begin{pmatrix}-1+4&-7+8\\2&4\end{pmatrix}
=\begin{pmatrix}3&1\\2&4\end{pmatrix}=B.
$$

The inverse on the left cancels $A$ without changing the factor order.
