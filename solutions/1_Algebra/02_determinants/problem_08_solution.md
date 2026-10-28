### Exercise 8. Determinant of a Product
Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

> **Why this exercise:** organizes how determinants behave with respect to products and inverses.

## Solution

For square matrices of the same size, $\det(AB)=\det A\det B$. Therefore

$$
\det(AB)=3(-5)=-15,\qquad
\det(BA)=(-5)3=-15.
$$

Since $\det A=3\ne0$, $A^{-1}$ exists, with determinant $1/3$. Thus

$$
\det(A^{-1}B)=\frac{\det B}{\det A}=-\frac53.
$$

The first two determinants agree because scalar multiplication commutes; equality of determinants does not require equality of the matrices $AB$ and $BA$.

For verification, $A(A^{-1}B)=B$, and the determinants satisfy $3(-5/3)=-5=\det B$.
