### Exercise 2. Addition and Scalar Multiplication
For

$$
A=
\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}
$$

compute

$$
A+B,\qquad A-B,\qquad 3A-2B.
$$

Explain why matrix addition is possible only for matrices of the same size.

> **Why this exercise:** reinforces entry-by-entry operations and the importance of compatible dimensions.

## Solution

Perform each operation entry by entry:

$$
A+B=\begin{pmatrix}1+4&2-2\\-1+0&3+5\end{pmatrix}
=\begin{pmatrix}5&0\\-1&8\end{pmatrix},
$$

$$
A-B=\begin{pmatrix}1-4&2-(-2)\\-1-0&3-5\end{pmatrix}
=\begin{pmatrix}-3&4\\-1&-2\end{pmatrix},
$$

$$
3A-2B=\begin{pmatrix}3&6\\-3&9\end{pmatrix}
-\begin{pmatrix}8&-4\\0&10\end{pmatrix}
=\begin{pmatrix}-5&10\\-3&-1\end{pmatrix}.
$$

Addition requires equal sizes so that every entry has a corresponding entry to add. For verification, adding $B$ to the computed $A-B$ recovers $\begin{pmatrix}1&2\\-1&3\end{pmatrix}=A$.
