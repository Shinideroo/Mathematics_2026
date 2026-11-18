### Problem 10. Definite Integral and Checking the Result
Before carrying out the exact calculation, estimate the possible range of values of the integral

$$
\int_0^2(x^2+1)\,dx,
$$

using

$$
1\le x^2+1\le5
$$

on $[0,2]$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

> **Why this problem:** it teaches how to predict the possible range of a result and check the calculation.

## Solution

First apply the supplied bounds over an interval of length $2$:

$$
2\le\int_0^2(x^2+1)\,dx\le10.
$$

Now use the antiderivative $x^3/3+x$:

$$
\int_0^2(x^2+1)\,dx
=\left[\frac{x^3}{3}+x\right]_0^2
=\frac83+2=\frac{14}{3}.
$$

Since $2<14/3<10$, the exact answer is consistent with the estimate. Differentiating $x^3/3+x$ returns the integrand, verifying the antiderivative.

The bounds can detect errors that produce a negative answer or a value outside $[2,10]$, such as an incorrect sign or scale factor. They cannot rule out every incorrect value within that interval.
