### Exercise 9. Area and the Determinant
The vectors

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

> **Why this exercise:** gives the determinant a geometric interpretation and distinguishes its sign from the value of the area.

## Solution

Put the spanning vectors in the columns of a matrix. The parallelogram's area is the absolute value of its determinant:

$$
\det[\,u\ v\,]=\det\begin{pmatrix}3&1\\1&4\end{pmatrix}
=3\cdot4-1\cdot1=11,
\qquad \text{area}=|11|=11.
$$

Reversing the vector order swaps columns and changes the sign:

$$
\det[\,v\ u\,]=\det\begin{pmatrix}1&3\\4&1\end{pmatrix}
=1-12=-11.
$$

Thus orientation reverses, while the area remains $|-11|=11$ square units. The direct second calculation verifies the column-swap property.
