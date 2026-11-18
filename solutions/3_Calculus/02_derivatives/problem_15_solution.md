### Problem 15. The Difference Quotient as a Check of the Derivative
Choose one function from the problem set and a point $x_0$ at which the derivative exists. Compute $f'(x_0)$ exactly, and then calculate

$$
\frac{f(x_0+h)-f(x_0)}h
$$

for $h=1$, $0.1$, and $0.01$. Compare the values with $f'(x_0)$ and explain why the difference quotient approaching a single number is consistent with the definition of the derivative, while a few computations do not replace a limit argument.

> **Why this problem:** it connects the definition of the derivative with concrete calculations and teaches the distinction between observation and proof.

## Solution

Choose $f(x)=x^2$ from Problem 11 and $x_0=1$. The exact derivative is $f'(1)=2$.

For $h\ne0$,

$$
\frac{f(1+h)-f(1)}h
=\frac{(1+h)^2-1}{h}=2+h.
$$

| $h$ | Difference quotient |
| --- | --- |
| $1$ | $3$ |
| $0.1$ | $2.1$ |
| $0.01$ | $2.01$ |

These values approach the exact derivative. The error is exactly $h$, so it tends to zero from either side. This identity proves the limiting claim; the three numerical observations alone would not control all smaller increments and do not replace the limit argument.
