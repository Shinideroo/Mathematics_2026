### Problem 2. Powers, Roots, and the Domain
For

$$
f(x)=2\sqrt{x}-\frac{3}{x^2}+x^{3/2}
$$

1. rewrite the function using powers,
2. determine the domain,
3. compute the derivative,
4. compare the domain of the function with the domain of its derivative.

> **Why this problem:** it teaches how to rewrite different forms so that the power rule can be applied and how to keep track of the domain.

## Solution

Rewrite

$$
f(x)=2x^{1/2}-3x^{-2}+x^{3/2}.
$$

The square root requires $x\ge0$ and the denominator requires $x\ne0$, so the original domain is $(0,\infty)$.

Apply the power rule there:

$$
f'(x)=x^{-1/2}+6x^{-3}+\frac32x^{1/2}
=\frac1{\sqrt x}+\frac6{x^3}+\frac32\sqrt x.
$$

The derivative has the same domain $(0,\infty)$; the apparent endpoint $0$ was already excluded from the function. As a sign check, differentiating the negative reciprocal-square term gives $(-3)(-2)x^{-3}=6x^{-3}$, explaining its positive sign.
