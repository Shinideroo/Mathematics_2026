### Problem 11. Choose the Method First
For each integral, first write which method you choose and how you recognize it, and then compute:

1. $\int\sin(3x)\,dx$,
2. $\int x\ln x\,dx$,
3. $\int\frac{x}{\sqrt{x^2+1}}\,dx$.

> **Why this problem:** it tests the choice of method based on the structure of the problem.

## Solution

1. **Substitution:** the inner function is $3x$, whose derivative is the constant $3$. Set $u=3x$:

$$
\int\sin(3x)\,dx=\frac13\int\sin u\,du
=-\frac13\cos(3x)+C.
$$

Its derivative is $\sin(3x)$.

2. **Integration by parts:** differentiating $\ln x$ simplifies it, while $x$ is easy to integrate. On $x>0$, use $u=\ln x$ and $dv=x\,dx$:

$$
\int x\ln x\,dx
=\frac{x^2}{2}\ln x-\int\frac{x}{2}\,dx
=\frac{x^2}{2}\ln x-\frac{x^2}{4}+C.
$$

Differentiation gives $x\ln x+x/2-x/2=x\ln x$.

3. **Substitution:** the derivative of $x^2+1$ is twice the numerator. Set $u=x^2+1$:

$$
\int\frac{x}{\sqrt{x^2+1}}\,dx
=\frac12\int u^{-1/2}\,du
=\sqrt{x^2+1}+C.
$$

The derivative is $x/\sqrt{x^2+1}$, verifying the result on all of $\mathbb R$.
