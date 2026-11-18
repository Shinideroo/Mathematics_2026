### Exercise 7. Inverse of a Product
For

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
2 & 0 \\
0 & 3 \\
\end{pmatrix}
$$

compute $(AB)^{-1}$ and $B^{-1}A^{-1}$. Check that the results are the same and explain the meaning of the reversed order.

> **Why this exercise:** reinforces the inverse-of-a-product property and requires its interpretation.

## Solution

First multiply and invert:

$$
AB=\begin{pmatrix}2&3\\0&3\end{pmatrix},
\qquad
(AB)^{-1}=\frac16\begin{pmatrix}3&-3\\0&2\end{pmatrix}
=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}.
$$

Separately,

$$
B^{-1}=\begin{pmatrix}\frac12&0\\0&\frac13\end{pmatrix},
\quad A^{-1}=\begin{pmatrix}1&-1\\0&1\end{pmatrix},
\quad B^{-1}A^{-1}=\begin{pmatrix}\frac12&-\frac12\\0&\frac13\end{pmatrix}.
$$

The results coincide. In $ABx$, $B$ acts first and $A$ second; to undo them, undo $A$ first and $B$ second. Algebraically,

$$
(AB)(B^{-1}A^{-1})=AIA^{-1}=I,
\qquad
(B^{-1}A^{-1})(AB)=B^{-1}IB=I.
$$
