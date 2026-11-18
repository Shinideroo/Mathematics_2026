### Exercise 13. Undoing a Composite Transformation
The matrices

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

> **Why this exercise:** reinforces the inverse of a product in a less direct configuration.

## Solution

First compute the composite:

$$
T=HS=\begin{pmatrix}2&1\\0&1\end{pmatrix},
\qquad
T^{-1}=\frac12\begin{pmatrix}1&-1\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
$$

Alternatively,

$$
S^{-1}H^{-1}
=\begin{pmatrix}\frac12&0\\0&1\end{pmatrix}
\begin{pmatrix}1&-1\\0&1\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&1\end{pmatrix}.
$$

The two methods agree. The incorrect order gives

$$
H^{-1}S^{-1}=\begin{pmatrix}\frac12&-1\\0&1\end{pmatrix},
\qquad
T(H^{-1}S^{-1})=\begin{pmatrix}1&-1\\0&1\end{pmatrix}\ne I.
$$

In contrast, $TT^{-1}=I$. Since $T$ scales first and shears second, its inverse must undo the shear first and scaling second.
