### Exercise 1. Dominant Terms in a Sequence
Compute

$$
\lim_{n\to\infty}\frac{4n^2-3n+1}{2n^2+5n-7}.
$$

Explain why the highest-degree terms determine the result.

> **Why this exercise:** introduces the idea of a dominant term and teaches how to simplify the behavior of expressions for large arguments.

## Solution

Divide numerator and denominator by $n^2$:

$$
\frac{4n^2-3n+1}{2n^2+5n-7}
=\frac{4-3/n+1/n^2}{2+5/n-7/n^2}\longrightarrow\frac42=2.
$$

Thus the limit is $2$. The lower-degree terms become zero after division, whereas the denominator approaches the nonzero number $2$, allowing the quotient limit rule.

For a check of approach, the original expression minus $2$ is

$$
\frac{-13n+15}{2n^2+5n-7}\longrightarrow0.
$$

The denominator is zero at $n=1$; the sequence expression is defined for all integers $n\ge2$, which is sufficient for its limit at infinity.
