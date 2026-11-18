### Exercise 2. Different Growth Rates
Compute

$$
\lim_{n\to\infty}\frac{3n+1}{n^2+4},\qquad \lim_{n\to\infty}\frac{2n^3-n}{5n^2+1}.
$$

Compare the two cases and formulate a general observation about the degrees of the polynomials in the numerator and denominator.

> **Why this exercise:** teaches how to compare growth rates and recognize qualitatively different cases.

## Solution

For the first limit, divide by $n^2$:

$$
\frac{3n+1}{n^2+4}=\frac{3/n+1/n^2}{1+4/n^2}\longrightarrow0.
$$

For the second, factor out the remaining growth:

$$
\frac{2n^3-n}{5n^2+1}
=n\,\frac{2-1/n^2}{5+1/n^2}\longrightarrow+\infty.
$$

Indeed, the factor after $n$ tends to $2/5>0$, so the expression grows without bound.

In a quotient of polynomials with nonzero leading coefficients, a smaller numerator degree gives limit $0$; equal degrees give the ratio of leading coefficients; a larger numerator degree gives unbounded magnitude, with sign determined by the leading coefficients as $n\to+\infty$. These results also check the expected growth orders $3/n$ and $(2/5)n$ here.
