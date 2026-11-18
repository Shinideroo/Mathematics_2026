### Exercise 12. Homogeneous System
Solve

$$
\begin{cases}
x+2y-z=0, \\
2x+4y-2z=0, \\
x-y+2z=0.
\end{cases}
$$

Give all solutions in parametric form and explain why $(0,0,0)$ always satisfies a homogeneous system.

> **Why this exercise:** shows the special case of a system with a zero right-hand side without introducing additional theory.

## Solution

Use $R_2\leftarrow R_2-2R_1$ and subtract equation one from equation three. The independent equations become

$$
x+2y-z=0,\qquad -3y+3z=0.
$$

Thus $z=y$. Set $y=s$; then $z=s$ and $x=-s$. All solutions are

$$
(x,y,z)=(-s,s,s),\qquad s\in\mathbb R.
$$

Verification gives $-s+2s-s=0$, twice that value for the second equation, and $-s-s+2s=0$ for the third.

The zero vector corresponds to $s=0$. In any homogeneous system every equation has zero right-hand side, so substituting all unknowns equal to zero always satisfies it.
