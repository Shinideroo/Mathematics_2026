### Exercise 9. Composing Transformations
Let

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For

$$
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

> **Why this exercise:** interprets matrix multiplication as composition of transformations.

## Solution

The rightmost transformation acts first:

$$
Sx=\begin{pmatrix}2\\2\end{pmatrix},
\qquad RSx=R\begin{pmatrix}2\\2\end{pmatrix}
=\begin{pmatrix}-2\\2\end{pmatrix}.
$$

In the other order,

$$
Rx=\begin{pmatrix}-2\\1\end{pmatrix},
\qquad SRx=S\begin{pmatrix}-2\\1\end{pmatrix}
=\begin{pmatrix}-4\\1\end{pmatrix}.
$$

Thus $RSx\ne SRx$. Scaling doubles the horizontal component. When scaling precedes rotation, that doubled component becomes vertical; when scaling follows rotation, it doubles the new horizontal component.

As a check,

$$
RS=\begin{pmatrix}0&-1\\2&0\end{pmatrix},
\qquad SR=\begin{pmatrix}0&-2\\1&0\end{pmatrix}.
$$

Multiplying each by $x$ reproduces the corresponding result.
