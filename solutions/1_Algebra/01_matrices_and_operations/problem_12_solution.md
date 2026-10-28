### Exercise 12. Formula for a Matrix Power
Let

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}.
$$

Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

> **Why this exercise:** teaches how to recognize a pattern and formulate a generalization from several computations.

## Solution

Successive multiplication gives

$$
A^2=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad
A^3=\begin{pmatrix}1&3\\0&1\end{pmatrix},\qquad
A^4=\begin{pmatrix}1&4\\0&1\end{pmatrix}.
$$

Each multiplication by $A$ adds one to the upper-right entry. The conjecture is

$$
A^n=\begin{pmatrix}1&n\\0&1\end{pmatrix}\qquad(n\geq0).
$$

For $n=0$ the expression is $I=A^0$. Assume it holds for an integer $n\geq0$. Then

$$
A^{n+1}=A^nA
=\begin{pmatrix}1&n\\0&1\end{pmatrix}\begin{pmatrix}1&1\\0&1\end{pmatrix}
=\begin{pmatrix}1&n+1\\0&1\end{pmatrix}.
$$

This is exactly the formula for $n+1$. The base case and induction step prove the conjecture for every nonnegative integer.
