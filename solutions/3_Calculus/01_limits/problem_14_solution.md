### Exercise 14. A $0/0$ Limit with Trigonometry
Compute

$$
\lim_{x\to0}\frac{1-\cos x}{x^2}.
$$

Justify the result without using l'Hôpital's rule, using a trigonometric identity and the fundamental limit.

> **Why this exercise:** requires combining two known tools in one argument.

## Solution

Use $1-\cos x=2\sin^2(x/2)$:

$$
\frac{1-\cos x}{x^2}
=\frac12\left(\frac{\sin(x/2)}{x/2}\right)^2
\longrightarrow\frac12.
$$

The last step uses the fundamental trigonometric limit, with angles in radians. This proves the result without l'Hôpital's rule.

As a separate consistency check, rationalization gives

$$
\frac{1-\cos x}{x^2}
=\frac{(\sin x/x)^2}{1+\cos x},
$$

whose numerator tends to $1$ and denominator to $2$, confirming $1/2$.
