### Exercise 4. Triangular Matrix
Without expanding the determinant, compute

$$
\det
\begin{pmatrix}
2 & 4 & 1 \\
0 & -3 & 5 \\
0 & 0 & 7 \\
\end{pmatrix}.
$$

State the rule for an arbitrary triangular matrix and explain it using this example.

> **Why this exercise:** reinforces an important property of triangular matrices.

## Solution

The matrix is upper triangular: every entry below the main diagonal is zero. Its determinant is the product of its diagonal entries:

$$
\det A=2(-3)7=-42.
$$

For any upper or lower triangular $n\times n$ matrix $T$,

$$
\det T=\prod_{i=1}^n t_{ii}.
$$

In the determinant sum, only the main-diagonal product can be nonzero: every other permutation selects at least one entry in the zero triangular region. Here that surviving product is precisely $2(-3)7$, so no expansion is needed.
