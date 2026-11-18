### Problem 13. An Integral Depending on the Upper Limit
Let

$$
F(x)=\int_0^x(t^2+1)\,dt.
$$

Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

> **Why this problem:** it connects differentiation and integration through the idea of accumulation.

## Solution

Treat $t$ as the integration variable and $x$ as the upper endpoint:

$$
F(x)=\left[\frac{t^3}{3}+t\right]_0^x
=\frac{x^3}{3}+x.
$$

Consequently,

$$
F'(x)=x^2+1,
$$

exactly the original integrand evaluated at $t=x$. This is the fundamental theorem of calculus, applicable because $t^2+1$ is continuous everywhere.

For a small increment $h$, $F(x+h)-F(x)=\int_x^{x+h}(t^2+1)\,dt$ is approximately $(x^2+1)h$. Dividing by $h$ and taking its limit gives the local accumulation rate $x^2+1$.

As a check, $F(0)=0$ and differentiating the explicit polynomial recovers that same rate. For $x<0$, the integral is oriented (signed accumulation), not an unsigned area.
