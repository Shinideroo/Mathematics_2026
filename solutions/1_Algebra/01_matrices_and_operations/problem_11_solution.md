### Exercise 11. When Do Matrices Commute?
Given

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
$$

Find the conditions on $a,b,c,d$ under which $AB=BA$. Describe the general form of all such matrices $B$.

> **Why this exercise:** deepens the idea of noncommutativity by finding the conditions under which commutativity does hold.

## Solution

Compute both products:

$$
AB=\begin{pmatrix}a+c&b+d\\c&d\end{pmatrix},
\qquad BA=\begin{pmatrix}a&a+b\\c&c+d\end{pmatrix}.
$$

Equality of corresponding entries requires $a+c=a$, $b+d=a+b$, and $d=c+d$; the lower-left entries already agree. These conditions reduce to $c=0$ and $d=a$, with $b$ unrestricted.

Therefore the general form is

$$
B=\begin{pmatrix}a&b\\0&a\end{pmatrix},
$$

where $a,b$ are arbitrary scalars. Substitution into both products yields $\begin{pmatrix}a&a+b\\0&a\end{pmatrix}$, verifying sufficiency as well as necessity.
