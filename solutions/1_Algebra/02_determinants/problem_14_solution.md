### Exercise 14. A System of Equations and the Determinant
Consider the system $Ax=b$, where

$$
A=
\begin{pmatrix}
1 & 2 \\
k & 4 \\
\end{pmatrix}.
$$

For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

> **Why this exercise:** connects the determinant with uniqueness of solutions and requires distinguishing the exceptional cases.

## Solution

The determinant is

$$
\det A=1\cdot4-2k=4-2k.
$$

A square system has exactly one solution for every right-hand side precisely when its coefficient matrix is invertible. Consequently, the required values are all $k\ne2$.

For $k=2$, the equations are

$$
x_1+2x_2=b_1,\qquad 2x_1+4x_2=b_2.
$$

The second left-hand side is twice the first, so consistency requires $b_2=2b_1$.

- Choose $b=\begin{pmatrix}1\\2\end{pmatrix}$. Every vector $x=\begin{pmatrix}1-2s\\s\end{pmatrix}$, with $s\in\mathbb R$, satisfies both equations, giving infinitely many solutions.
- Choose $b=\begin{pmatrix}1\\0\end{pmatrix}$. The first equation would force the second left-hand side to equal $2$, contradicting its required value $0$, so there is no solution.

Substitution verifies the infinite family and the stated inconsistency.
