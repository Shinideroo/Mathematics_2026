### Exercise 7. Limit at a Point and Canceling a Factor
Compute

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}.
$$

Explain why the value of the function at $x=3$ is not needed to compute the limit.

> **Why this exercise:** separates the concept of a limit from the value of a function at a point.

## Solution

Factor the numerator:

$$
x^2-4x+3=(x-1)(x-3).
$$

For $x\ne3$, the quotient equals $x-1$. Therefore

$$
\lim_{x\to3}\frac{x^2-4x+3}{x-3}
=\lim_{x\to3}(x-1)=2.
$$

Cancellation is valid in the punctured neighborhood used for a limit; the original expression remains undefined at $3$. A limit concerns nearby values, so no value at $3$ is needed. Extending the function by setting its value there to $2$ would make it continuous, checking the removable nature of the gap.
