### Exercise 8. Two Systems with the Same Coefficient Matrix
Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

> **Why this exercise:** shows the role of the coefficient matrix independently of the right-hand side.

## Solution

Eliminate $x$ using $R_2\leftarrow R_2-\frac12R_1$.

For the first system:

$$
\begin{pmatrix}2&1&\mid&5\\1&-1&\mid&1\end{pmatrix}
\longrightarrow
\begin{pmatrix}2&1&\mid&5\\0&-3/2&\mid&-3/2\end{pmatrix}.
$$

Thus $y=1$ and $x=2$.

For the second:

$$
\begin{pmatrix}2&1&\mid&1\\1&-1&\mid&4\end{pmatrix}
\longrightarrow
\begin{pmatrix}2&1&\mid&1\\0&-3/2&\mid&7/2\end{pmatrix}.
$$

Thus $y=-7/3$ and $x=(1+7/3)/2=5/3$.

The row multiplier and resulting coefficient block are identical because the original coefficient matrix is identical. Only the transformed right-hand side changes; the same row operation can therefore be applied to both right-hand sides at once.

Checks: $2(2)+1=5$, $2-1=1$; and $2(5/3)-7/3=1$, $5/3+7/3=4$.
