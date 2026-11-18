### Problem 6. When Does a Logarithm Appear from an Integral?
Compute

$$
\int\frac{2x}{x^2+5}\,dx.
$$

Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

> **Why this problem:** it teaches how to recognize the structure “derivative of the denominator over the denominator.”

## Solution

The numerator is the derivative of the denominator. Put $u=x^2+5$, so $du=2x\,dx$:

$$
\int\frac{2x}{x^2+5}\,dx
=\int\frac1u\,du
=\ln|u|+C
=\ln(x^2+5)+C.
$$

The absolute value can be dropped because $x^2+5>0$ for every real $x$. The logarithm appears because its derivative is $1/u$; substitution transfers that pattern to a nontrivial denominator.

Verification:

$$
\frac{d}{dx}\ln(x^2+5)=\frac{2x}{x^2+5}.
$$
