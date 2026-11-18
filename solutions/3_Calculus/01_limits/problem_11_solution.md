### Exercise 11. An n-th Root
Compute

$$
\lim_{n\to\infty}\sqrt[n]{5^n+2^n}.
$$

Explain which term dominates and why the transformation looks different from the case of a quotient of polynomials.

> **Why this exercise:** extends the idea of dominance to exponential expressions.

## Solution

Factor out the dominant exponential inside the root:

$$
\sqrt[n]{5^n+2^n}
=5\left(1+\left(\frac25\right)^n\right)^{1/n}.
$$

Since $0<(2/5)^n\le1$,

$$
5\le\sqrt[n]{5^n+2^n}\le5\,2^{1/n}.
$$

The upper and lower bounds tend to $5$, proving the limit is $5$ by squeezing.

The $5^n$ term dominates because $(2/5)^n\to0$. Unlike a polynomial quotient, the whole expression is inside an $n$-th root, so factoring $5^n$ produces the factor $5$, not a quotient of leading coefficients. The squeeze bounds verify that the smaller exponential cannot change the limit.
