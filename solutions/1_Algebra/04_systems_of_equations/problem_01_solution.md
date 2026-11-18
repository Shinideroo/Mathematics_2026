### Exercise 1. From a System to a Matrix
Write the system

$$
\begin{cases}
2x-y+z=4, \\
x+3y-2z=1, \\
3x+y+z=7.
\end{cases}
$$

in the form $Ax=b$.
Identify the coefficient matrix, the vector of unknowns, and the right-hand side vector. Explain how each row of the matrix corresponds to one equation.

> **Why this exercise:** teaches how to move between a system of equations and matrix notation.

## Solution

Keep the unknown order $(x,y,z)$. The matrix form is

$$
\underbrace{\begin{pmatrix}2&-1&1\\1&3&-2\\3&1&1\end{pmatrix}}_{A}
\underbrace{\begin{pmatrix}x\\y\\z\end{pmatrix}}_{\text{vector of unknowns}}
=\underbrace{\begin{pmatrix}4\\1\\7\end{pmatrix}}_{b}.
$$

Each row lists the coefficients of one equation in that fixed order; $b$ lists the corresponding constants.

Verification is obtained by multiplying out the left side:

$$
Ax=\begin{pmatrix}2x-y+z\\x+3y-2z\\3x+y+z\end{pmatrix}.
$$

Equating its entries with those of $b$ recovers exactly the original system. Here the symbol $x$ in $Ax=b$ denotes the whole unknown vector, while $x$ in its first entry is the first scalar unknown.
