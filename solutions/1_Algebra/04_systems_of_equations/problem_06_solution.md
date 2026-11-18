### Exercise 6. A System with a Parameter — Which Cases Actually Occur?
Analyze, depending on the parameter $a$, the system

$$
\begin{cases}
x+y=2, \\
ax+ay=4.
\end{cases}
$$

Among the three possibilities — exactly one solution, infinitely many solutions, no solution — determine which actually occur and for which values of $a$. If one type cannot occur, explain why.

> **Why this exercise:** teaches how to analyze a parameter without assuming in advance that all theoretically possible cases must occur in a specific system.

## Solution

Subtract $a$ times the first equation from the second:

$$
\begin{pmatrix}1&1&\mid&2\\a&a&\mid&4\end{pmatrix}
\longrightarrow
\begin{pmatrix}1&1&\mid&2\\0&0&\mid&4-2a\end{pmatrix}.
$$

- If $a=2$, the last row is zero. All solutions are $(x,y)=(2-s,s)$, $s\in\mathbb R$, so there are infinitely many.
- If $a\ne2$, the last row asserts $0=4-2a\ne0$, so there is no solution.

Exactly one solution cannot occur: the two coefficient rows are always proportional and cannot determine two variables independently. For verification at $a=2$, substitution gives $x+y=2$ and $2x+2y=4$ for every $s$.
