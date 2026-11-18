### Exercise 8. Inverse of a Transformation
The matrix

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

> **Why this exercise:** gives the inverse the interpretation of undoing a transformation.

## Solution

Invert the nonzero diagonal entries:

$$
S^{-1}=\begin{pmatrix}\frac12&0\\0&2\end{pmatrix}.
$$

$S$ doubles horizontal distances and halves vertical distances. Its inverse halves the horizontal coordinate and doubles the vertical coordinate, undoing that scaling.

For example,

$$
\begin{pmatrix}1\\2\end{pmatrix}
\xrightarrow{S}\begin{pmatrix}2\\1\end{pmatrix}
\xrightarrow{S^{-1}}\begin{pmatrix}1\\2\end{pmatrix}.
$$

Also $SS^{-1}=S^{-1}S=\operatorname{diag}(1,1)=I$, verifying the inverse on all vectors.
