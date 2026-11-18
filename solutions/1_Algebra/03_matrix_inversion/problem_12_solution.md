### Exercise 12. Finding Inverses Without Starting from Scratch
It is known that

$$
A^{-1}=
\begin{pmatrix}
2 & -1 \\
-3 & 2 \\
\end{pmatrix}.
$$

Without finding $A$, compute $(3A)^{-1}$, $(A^T)^{-1}$, and $(A^2)^{-1}$. Justify each result using the appropriate property.

> **Why this exercise:** teaches how to use inverse properties instead of carrying out unnecessary full calculations.

## Solution

Write $M=A^{-1}$, using the given entries. Scalar, transpose, and product inverse identities give

$$
(3A)^{-1}=\frac13M=\begin{pmatrix}\frac23&-\frac13\\-1&\frac23\end{pmatrix},
$$

$$
(A^T)^{-1}=M^T=\begin{pmatrix}2&-3\\-1&2\end{pmatrix},
$$

$$
(A^2)^{-1}=M^2
=\begin{pmatrix}4+3&-2-2\\-6-6&3+4\end{pmatrix}
=\begin{pmatrix}7&-4\\-12&7\end{pmatrix}.
$$

These properties follow directly from the inverse definition. For verification, $(3A)(M/3)=AM=I$, $A^TM^T=(MA)^T=I$, and $A^2M^2=A(AM)M=I$. Thus no entries of $A$ need to be found.
