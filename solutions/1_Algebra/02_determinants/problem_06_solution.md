### Exercise 6. Parameter and Invertibility
For

$$
A(t)=
\begin{pmatrix}
t & 1 \\
2 & t \\
\end{pmatrix}
$$

find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

> **Why this exercise:** shows how the determinant can be used to study a family of matrices depending on a parameter.

## Solution

Compute the determinant using $ad-bc$:

$$
\det A(t)=t^2-2.
$$

A square matrix fails to be invertible exactly when its determinant is zero. Hence

$$
t^2-2=0
\quad\Longleftrightarrow\quad
t=\sqrt2\ \text{or}\ t=-\sqrt2.
$$

At either value, $t^2=2$, so row two equals $t$ times row one: $t(t,1)=(2,t)$. This verifies dependence and noninvertibility. For every other real $t$, the determinant is nonzero and the matrix is invertible.
