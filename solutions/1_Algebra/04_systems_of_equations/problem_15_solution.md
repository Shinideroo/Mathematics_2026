### Exercise 15. Classifying Three Systems
For each of the following systems, perform only as much elimination as necessary to recognize its type:

**System 1**

$$
\begin{cases}
x+y=2, \\
x-y=0,
\end{cases}
$$

**System 2**

$$
\begin{cases}
x+y=2, \\
2x+2y=4,
\end{cases}
$$

**System 3**

$$
\begin{cases}
x+y=2, \\
2x+2y=5.
\end{cases}
$$

For each, justify the classification: one solution, infinitely many solutions, or no solution.

> **Why this exercise:** brings together the three basic cases and requires recognizing them from the structure after elimination.

## Solution

**System 1:** subtract equation one from equation two to get $-2y=-2$. Hence $y=1$, $x=1$: exactly one solution. Check $1+1=2$ and $1-1=0$.

**System 2:** subtract twice equation one from equation two to get $0=0$. One independent equation remains, so there are infinitely many solutions:

$$
(x,y)=(2-s,s),\qquad s\in\mathbb R.
$$

Substitution gives $x+y=2$ and $2x+2y=4$ for every $s$.

**System 3:** the same elimination gives $0=5-4=1$, a contradiction. Thus there is no solution.

A pivot for each variable gives uniqueness, a consistent free variable gives infinitely many solutions, and a contradictory row gives no solution.
