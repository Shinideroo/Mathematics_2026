### Exercise 7. Choosing a Method Deliberately
Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

> **Why this exercise:** practices choosing a method based on the structure of the problem instead of solving another small system by two methods.

## Solution

1. **Triangular system:** use back substitution. From $4y=8$, obtain $y=2$; then $2x-2=3$ gives $x=5/2$. Check: $2(5/2)-2=3$ and $4(2)=8$.
2. **Three right-hand sides with known inverse:** use $x_i=A^{-1}b_i$ for each $i$. The already known inverse is reused in three matrix-vector products. Recomputing the inverse or repeating elimination from scratch is unnecessary. Each answer can be checked with $Ax_i=b_i$.
3. **One $3\times3$ system with no given inverse:** apply Gaussian elimination to $[A\mid b]$, then back substitute if there are three pivots. If elimination reveals free variables or a contradictory row, report the appropriate solution type. Computing all entries of $A^{-1}$ is unnecessary for one right-hand side.

The choice depends on the triangular structure, what is already available, and how many right-hand sides must be handled.
