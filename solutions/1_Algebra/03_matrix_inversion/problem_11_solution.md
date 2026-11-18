### Exercise 11. Parameter and Invertibility
For

$$
A(t)=
\begin{pmatrix}
1 & t \\
t & 1 \\
\end{pmatrix}
$$

find all $t$ for which the matrix is invertible, and then give a formula for $A(t)^{-1}$. Explain what happens to this formula at the excluded values.

> **Why this exercise:** combines a parameter, determinant, and an explicit inverse formula in one problem.

## Solution

Compute $\det A(t)=1-t^2$. Therefore $A(t)$ is invertible exactly when $t\ne1,-1$, and the inverse formula gives

$$
A(t)^{-1}=\frac1{1-t^2}\begin{pmatrix}1&-t\\-t&1\end{pmatrix}.
$$

Verification:

$$
A(t)\begin{pmatrix}1&-t\\-t&1\end{pmatrix}
=\begin{pmatrix}1-t^2&0\\0&1-t^2\end{pmatrix}.
$$

Division by $1-t^2$ gives $I$ at every permitted value. At $t=1$ the rows coincide; at $t=-1$ they are negatives. The denominator vanishes at both values, reflecting actual noninvertibility, not merely a defect of the formula.
