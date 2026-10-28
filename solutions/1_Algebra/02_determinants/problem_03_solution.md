### Exercise 3. Swapping Two Rows
For

$$
A=
\begin{pmatrix}
1 & 2 & 0 \\
0 & 3 & 1 \\
2 & 1 & 1 \\
\end{pmatrix}
$$

compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

> **Why this exercise:** gives a second classical calculation with a $3\times3$ determinant while teaching the precise effect of a row swap on the sign of the determinant.

## Solution

Expand along the first row:

$$
\det A=1(3\cdot1-1\cdot1)-2(0\cdot1-1\cdot2)
=2+4=6.
$$

Swapping rows one and two gives

$$
B=\begin{pmatrix}0&3&1\\1&2&0\\2&1&1\end{pmatrix}.
$$

A single row swap changes the determinant's sign, so the prediction is $\det B=-6$.

Verify directly by first-row expansion:

$$
\det B=0-3(1\cdot1-0\cdot2)+1(1\cdot1-2\cdot2)
=-3-3=-6.
$$

The calculation agrees with the sign-change property.
