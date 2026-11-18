### Problem 9. A Logarithm and the Chain Rule
For

$$
f(x)=\ln(x^2+1)
$$

compute the derivative. Then determine the sign of $f'(x)$ for $x<0$, $x=0$, and $x>0$, and describe qualitatively how the function behaves around zero.

> **Why this problem:** it connects differentiation with sign analysis and the behavior of a function.

## Solution

Since $x^2+1>0$ for all real $x$, the domain is $\mathbb R$. The logarithm chain rule gives

$$
f'(x)=\frac{2x}{x^2+1}.
$$

The denominator is positive, so the derivative is negative for $x<0$, zero at $0$, and positive for $x>0$. The function decreases toward zero from the left and increases away from zero on the right. It has a global minimum $f(0)=0$.

Verification follows from $x^2+1\ge1$, which implies $\ln(x^2+1)\ge0$, with equality only at zero.
