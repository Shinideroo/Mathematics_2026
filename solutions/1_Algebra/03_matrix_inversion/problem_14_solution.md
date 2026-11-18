### Exercise 14. A Matrix That Is Its Own Inverse
Assume that a square matrix $A$ satisfies

$$
A^2=I.
$$

Show that

$$
A^{-1}=A.
$$

Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

> **Why this exercise:** requires using the definition of the inverse in a short argument and constructing an example independently, without introducing a new topic.

## Solution

The equation $A^2=I$ says both $AA=I$ and $AA=I$ in the two orders needed by the inverse definition. Thus $A$ itself is an inverse, and uniqueness of the inverse gives $A^{-1}=A$.

For an example different from $I$ and $-I$, choose

$$
A=\begin{pmatrix}1&0\\0&-1\end{pmatrix}.
$$

Then

$$
A^2=\begin{pmatrix}1&0\\0&1\end{pmatrix}=I.
$$

Geometrically, reflecting in the horizontal axis twice restores the original vector, which also verifies the example.
