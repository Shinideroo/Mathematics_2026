### Exercise 15. Associativity of Multiplication and Different Calculation Paths
Given

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 1 & 1 \\
\end{pmatrix},\quad B=
\begin{pmatrix}
1 & 0 \\
2 & 1 \\
-1 & 3 \\
\end{pmatrix},\quad C=
\begin{pmatrix}
2 & 1 \\
0 & -1 \\
\end{pmatrix}.
$$

Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

> **Why this exercise:** reinforces associativity by comparing two mathematically equivalent calculation paths.

## Solution

For the first grouping,

$$
AB=\begin{pmatrix}1+4+0&0+2+0\\0+2-1&0+1+3\end{pmatrix}
=\begin{pmatrix}5&2\\1&4\end{pmatrix},
$$

$$
(AB)C=\begin{pmatrix}10&5-2\\2&1-4\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
$$

For the second grouping,

$$
BC=\begin{pmatrix}2&1\\4&2-1\\-2&-1-3\end{pmatrix}
=\begin{pmatrix}2&1\\4&1\\-2&-4\end{pmatrix},
$$

$$
A(BC)=\begin{pmatrix}2+8+0&1+2+0\\0+4-2&0+1-4\end{pmatrix}
=\begin{pmatrix}10&3\\2&-3\end{pmatrix}.
$$

Agreement verifies the result and illustrates associativity: grouping can change while the factor order stays fixed.

For a standard dense calculation, count all scalar products and additions, including those involving zero. Multiplication of sizes $(m\times n)(n\times p)$ uses $mnp$ multiplications and $mp(n-1)$ additions.

| Grouping | Scalar multiplications | Scalar additions |
| --- | --- | --- |
| $(AB)C$ | $12+8=20$ | $8+4=12$ |
| $A(BC)$ | $12+12=24$ | $6+8=14$ |

The first grouping uses four fewer multiplications and two fewer additions. Skipping zeros or ones can change practical counts; this table specifies a consistent convention.
