### Exercise 7. Identity Matrix, Zero Matrix, and Powers
For

$$
A=
\begin{pmatrix}
2 & 1 \\
0 & 2 \\
\end{pmatrix}
$$

compute

$$
AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.
$$

Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

> **Why this exercise:** organizes the roles of neutral elements and reveals regularity in successive powers of a matrix.

## Solution

Here $I=\begin{pmatrix}1&0\\0&1\end{pmatrix}$ and $0=\begin{pmatrix}0&0\\0&0\end{pmatrix}$. They are the neutral elements for multiplication and addition, respectively:

$$
AI=IA=A+0=\begin{pmatrix}2&1\\0&2\end{pmatrix}.
$$

Successive multiplication gives

$$
A^2=\begin{pmatrix}4&2+2\\0&4\end{pmatrix}
=\begin{pmatrix}4&4\\0&4\end{pmatrix},
\qquad
A^3=A^2A=\begin{pmatrix}8&4+8\\0&8\end{pmatrix}
=\begin{pmatrix}8&12\\0&8\end{pmatrix}.
$$

The pattern for positive integers is

$$
A^n=\begin{pmatrix}2^n&n2^{n-1}\\0&2^n\end{pmatrix}.
$$

For verification, it holds at $n=1$. Multiplying the proposed expression by $A$ gives diagonal entries $2^{n+1}$ and upper-right entry $2^n+2n2^{n-1}=(n+1)2^n$, which proves the next case and hence the formula by induction. Also $A^0=I$.
