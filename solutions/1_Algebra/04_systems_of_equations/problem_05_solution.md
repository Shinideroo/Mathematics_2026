### Exercise 5. Row Echelon Form and Number of Solutions
For the augmented matrix

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

> **Why this exercise:** teaches how to read information about solutions directly from row echelon form.

## Solution

The nonzero rows represent

$$
x+2y-z=3,\qquad y+2z=1.
$$

There are three variables and two pivot columns, with no contradictory row. Hence one variable is free: let $z=s$. Back substitution gives

$$
y=1-2s,\qquad x=3-2(1-2s)+s=1+5s.
$$

Thus there are infinitely many solutions:

$$
(x,y,z)=(1+5s,1-2s,s),\qquad s\in\mathbb R.
$$

Check: $(1+5s)+2(1-2s)-s=3$ and $(1-2s)+2s=1$. The zero row imposes no additional condition.
