### Problem 9. Definite Integral and Geometric Area
Compute

$$
\int_{-1}^{2}x\,dx.
$$

Then separately compute the areas of the parts of the graph below and above the $x$-axis and explain the difference between the definite integral and geometric area.

> **Why this problem:** it clarifies the difference between signed accumulation and area.

## Solution

The antiderivative is $x^2/2$, so the fundamental theorem of calculus gives

$$
\int_{-1}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{-1}^{2}
=2-\frac12=\frac32.
$$

The part below the axis, from $-1$ to $0$, is a triangle of area $(1)(1)/2=1/2$. The part above, from $0$ to $2$, has area $(2)(2)/2=2$.

Thus the definite integral is signed area $2-1/2=3/2$, while the total geometric area is $2+1/2=5/2$. The triangle calculation independently verifies the integral and explains why the two quantities differ.
