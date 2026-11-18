### Exercise 2. Formula for a 2×2 Matrix
Find the inverse of

$$
A=
\begin{pmatrix}
3 & 2 \\
5 & 4 \\
\end{pmatrix}
$$

using the formula for a $2\times2$ matrix. At the end, check the result by computing one product with $A$.

> **Why this exercise:** teaches the simplest explicit formula for an inverse and requires verification using the definition.

## Solution

For $\begin{pmatrix}a&b\\c&d\end{pmatrix}$ with $ad-bc\ne0$, the inverse is $\frac1{ad-bc}\begin{pmatrix}d&-b\\-c&a\end{pmatrix}$. Here $\det A=12-10=2$, so

$$
A^{-1}=\frac12\begin{pmatrix}4&-2\\-5&3\end{pmatrix}.
$$

Check by multiplication:

$$
AA^{-1}=\frac12\begin{pmatrix}12-10&-6+6\\20-20&-10+12\end{pmatrix}
=\frac12\begin{pmatrix}2&0\\0&2\end{pmatrix}=I.
$$
