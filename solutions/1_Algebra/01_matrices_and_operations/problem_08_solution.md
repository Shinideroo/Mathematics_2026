### Exercise 8. Row Operations and Their Reversibility
For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

perform, in order:

1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

> **Why this exercise:** prepares for elimination by showing that row operations are controlled and reversible transformations of a matrix.

## Solution

Apply each operation to the current matrix. Subtracting twice row one from row two gives $(0,0,3)$:

$$
A_1=\begin{pmatrix}1&2&-1\\0&0&3\\-1&1&3\end{pmatrix}.
$$

Adding row one to row three gives $(0,3,2)$:

$$
A_2=\begin{pmatrix}1&2&-1\\0&0&3\\0&3&2\end{pmatrix}.
$$

Finally, interchange rows two and three:

$$
A_3=\begin{pmatrix}1&2&-1\\0&3&2\\0&0&3\end{pmatrix}.
$$

The individual inverse operations are:

1. $R_2\leftarrow R_2+2R_1$.
2. $R_3\leftarrow R_3-R_1$.
3. Interchange $R_2$ and $R_3$ again.

To verify the entire calculation, undo in reverse order: the swap recovers $A_2$, subtracting row one from row three recovers $A_1$, and adding twice row one to row two recovers $A$.
