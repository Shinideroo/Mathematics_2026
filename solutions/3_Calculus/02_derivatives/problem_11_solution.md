### Problem 11. Derivative from the Definition
Using only

$$
f'(x)=\lim_{h\to0}\frac{f(x+h)-f(x)}h,
$$

find the derivative of $f(x)=x^2$. Compare the result with the power rule and indicate where the limit is used in the calculation.

> **Why this problem:** it shows the origin of the power rule and the direct connection between the derivative and a limit.

## Solution

Use only the difference quotient. For $h\ne0$,

$$
\frac{f(x+h)-f(x)}h
=\frac{(x+h)^2-x^2}{h}
=\frac{2xh+h^2}{h}=2x+h.
$$

Now take the limit:

$$
f'(x)=\lim_{h\to0}(2x+h)=2x.
$$

The limit is used after cancellation: the extra term $h$ tends to zero. This agrees with the power rule for $x^2$, providing the requested comparison without using that rule in the derivation.
