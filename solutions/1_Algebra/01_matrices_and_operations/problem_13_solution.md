### Exercise 13. A Recurrence Written in Matrix Form
Let

$$
F=
\begin{pmatrix}
1 & 1 \\
1 & 0 \\
\end{pmatrix}.
$$

Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence

$$
0,1,1,2,3,5,8,\ldots
$$

and describe the relationship you observe. Then compute

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}
$$

and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

> **Why this exercise:** shows the connection between matrix powers and a simple numerical recurrence.

## Solution

Multiply each preceding power by $F$:

$$
F^2=\begin{pmatrix}2&1\\1&1\end{pmatrix},\quad
F^3=\begin{pmatrix}3&2\\2&1\end{pmatrix},\quad
F^4=\begin{pmatrix}5&3\\3&2\end{pmatrix},\quad
F^5=\begin{pmatrix}8&5\\5&3\end{pmatrix}.
$$

For example, the first row of $F^3=F^2F$ is $(2+1,2)=(3,2)$; subsequent powers use the same rule.

Write the given Fibonacci sequence as $f_0=0$, $f_1=1$, $f_{n+1}=f_n+f_{n-1}$. The relationship is

$$
F^n=\begin{pmatrix}f_{n+1}&f_n\\f_n&f_{n-1}\end{pmatrix}\qquad(n\geq1).
$$

For a general vector,

$$
F\begin{pmatrix}a\\b\end{pmatrix}=\begin{pmatrix}a+b\\a\end{pmatrix}.
$$

Thus $(f_{n+1},f_n)$ becomes $(f_{n+2},f_{n+1})$: the sum is created and the previous first term is retained. The power formula holds for $n=1$; left multiplication by $F$ adds its two rows and retains its previous first row, giving exactly the formula for $n+1$. This verifies the relationship inductively.
