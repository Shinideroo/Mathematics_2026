### Exercise 15. Combining Determinant Properties
Let $A$ and $B$ be invertible $2\times2$ matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

> **Why this exercise:** tests the transfer of several known properties into one short problem instead of checking a single property again with numbers.

## Solution

First use multiplicativity to separate the factors:

$$
\det(B^{-1}A^TB)=\det(B^{-1})\det(A^T)\det B.
$$

Next, use the inverse property $\det(B^{-1})=1/\det B$ and transpose invariance $\det(A^T)=\det A$:

$$
\det(B^{-1}A^TB)=\frac13(-2)3=-2.
$$

The factors involving $B$ cancel because $\det(B^{-1})\det B=\det(B^{-1}B)=\det I=1$. Invertibility guarantees the inverse exists and its determinant is defined.

For a consistency check, conjugating $A^T$ by $B$ only multiplies its determinant by $(\det B)^{-1}\det B=1$, so the answer must equal $\det(A^T)=\det A=-2$.
