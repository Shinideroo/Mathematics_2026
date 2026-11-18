### Exercise 10. Inverse of a Diagonal Matrix
Given

$$
D=
\begin{pmatrix}
2 & 0 & 0 \\
0 & -3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},\qquad E=
\begin{pmatrix}
2 & 0 & 0 \\
0 & 0 & 0 \\
0 & 0 & 5 \\
\end{pmatrix}.
$$

Without using Gauss–Jordan elimination, decide which matrix is invertible. For the invertible matrix, give the inverse and check the result by multiplication.

> **Why this exercise:** teaches how to recognize invertibility and the inverse without using a full procedure when the matrix structure gives the answer immediately.

## Solution

A diagonal matrix is invertible exactly when all diagonal entries are nonzero. Thus $D$ is invertible and

$$
D^{-1}=\begin{pmatrix}\frac12&0&0\\0&-\frac13&0\\0&0&\frac15\end{pmatrix}.
$$

Multiplying diagonal matrices multiplies corresponding diagonal entries, so

$$
DD^{-1}=D^{-1}D=\operatorname{diag}(2/2,(-3)(-1/3),5/5)=I.
$$

$E$ is not invertible: its middle diagonal entry is zero, and $E(0,1,0)^T=0$ despite $(0,1,0)^T\ne0$. This checks the failure directly.
