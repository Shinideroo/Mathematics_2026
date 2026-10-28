### Exercise 7. Using Properties Instead of Recomputing
Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

> **Why this exercise:** teaches how to use determinant properties instead of repeating a full calculation.

## Solution

For an $n\times n$ matrix, $\det(cA)=c^n\det A$, because each of its $n$ rows is scaled by $c$. Here $n=3$:

$$
\det(2A)=2^3(-4)=-32.
$$

Transposition preserves the determinant:

$$
\det(A^T)=\det A=-4.
$$

The determinant of a product is the product of the determinants:

$$
\det(A^2)=(\det A)^2=(-4)^2=16.
$$

Finally, scaling all three rows by $-1$ gives

$$
\det(-A)=(-1)^3(-4)=4.
$$

As a consistency check, $\det((-A)^2)=4^2=16=\det(A^2)$, in agreement with $(-A)^2=A^2$.
