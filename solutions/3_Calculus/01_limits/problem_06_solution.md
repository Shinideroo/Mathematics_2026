### Exercise 6. From a Sequence to a Function — Limit at Infinity
Compute

$$
\lim_{x\to\infty}\frac{3x^2-x+1}{5x^2+4x-2}.
$$

Compare the method with Exercise 1. Explain what changes when moving from $n$ to a real variable $x$, and what stays the same.

> **Why this exercise:** deliberately transfers a technique from sequence limits to function limits.

## Solution

Divide by $x^2$:

$$
\frac{3x^2-x+1}{5x^2+4x-2}
=\frac{3-1/x+1/x^2}{5+4/x-2/x^2}
\longrightarrow\frac35.
$$

Thus the limit is $3/5$. As in Exercise 1, the leading quadratic terms survive and all lower-degree terms vanish after division. The denominator tends to $5\ne0$.

The variable now takes all sufficiently large real values rather than just integers. The same algebra works because $1/x$ and $1/x^2$ tend to zero in either setting. As a check,

$$
\frac{3x^2-x+1}{5x^2+4x-2}-\frac35
=\frac{-17x+11}{5(5x^2+4x-2)}\longrightarrow0.
$$
