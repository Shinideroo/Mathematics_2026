### Problem 8. Two Exponential Functions
For

$$
f(x)=e^{2x-3}+5^x
$$

compute the derivative. Explain why the factor $2$ appears in the first term and why $\ln5$ appears in the second.

> **Why this problem:** it organizes two different mechanisms that produce additional factors.

## Solution

Apply the chain rule to the first term and the exponential-base rule to the second:

$$
f'(x)=2e^{2x-3}+5^x\ln5.
$$

The factor $2$ is the derivative of the exponent $2x-3$. To verify the second factor, write $5^x=e^{x\ln5}$; the chain rule then gives $e^{x\ln5}\ln5=5^x\ln5$.

Both derivatives are positive for every real $x$, consistent with the fact that both original exponential terms increase.
