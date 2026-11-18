### Exercise 5. The Classical Limit Leading to the Number $e$
Compute

$$
\lim_{n\to\infty}\left(1+\frac1n\right)^n.
$$

Calculate several values for increasing $n$ and compare the observed behavior with the value of the limit. Explain why a few values do not constitute a proof.

> **Why this exercise:** connects a central limit with intuition based on concrete terms of a sequence.

## Solution

The limit is the classical number

$$
\lim_{n\to\infty}\left(1+\frac1n\right)^n=e\approx2.718281828.
$$

For a limit argument, use the logarithm bound $u/(1+u)\le\ln(1+u)\le u$ for $u>0$. With $u=1/n$,

$$
\frac{n}{n+1}\le n\ln(1+1/n)\le1.
$$

Both bounds tend to $1$, so the logarithm of the sequence tends to $1$. Continuity of the exponential yields the limit $e$.

Numerical checks, rounded to six decimal places:

| $n$ | $(1+1/n)^n$ |
| --- | --- |
| $1$ | $2.000000$ |
| $10$ | $2.593742$ |
| $100$ | $2.704814$ |
| $1000$ | $2.716924$ |

The values support approach toward $e$ from below. A finite table cannot control all later terms; the bounding argument supplies that control.
