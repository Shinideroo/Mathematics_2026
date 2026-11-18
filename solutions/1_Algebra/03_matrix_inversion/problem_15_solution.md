### Exercise 15. Two Methods for Solving the Same System
For

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
7 \\
8 \\
\end{pmatrix}
$$

solve $Ax=b$ in two ways:

1. using $A^{-1}b$,
2. using Gaussian elimination.

Compare both solutions, the number of essential steps, and state which method was simpler in this example.

> **Why this exercise:** compares two known methods and prepares the student to choose a solution method consciously.

## Solution

**Inverse method.** The determinant is $5$, so

$$
A^{-1}=\frac15\begin{pmatrix}3&-1\\-1&2\end{pmatrix},
\qquad
x=A^{-1}b=\frac15\begin{pmatrix}21-8\\-7+16\end{pmatrix}
=\begin{pmatrix}13/5\\9/5\end{pmatrix}.
$$

**Gaussian elimination.** Starting with the augmented matrix, use $R_2\leftarrow R_2-\frac12R_1$:

$$
\begin{pmatrix}2&1&\mid&7\\1&3&\mid&8\end{pmatrix}
\longrightarrow
\begin{pmatrix}2&1&\mid&7\\0&5/2&\mid&9/2\end{pmatrix}.
$$

Back substitution gives $x_2=9/5$ and $x_1=(7-9/5)/2=13/5$, agreeing with the inverse method.

Counting broad stages, the inverse method computes a determinant, forms four inverse entries, and performs a matrix-vector product. Elimination uses one row replacement and two back-substitution equations. For one right-hand side, elimination is simpler here; a previously available inverse would change the comparison.

Check both equations:

$$
2(13/5)+9/5=7,\qquad 13/5+3(9/5)=8.
$$
