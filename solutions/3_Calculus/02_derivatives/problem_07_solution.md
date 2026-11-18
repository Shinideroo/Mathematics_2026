### Problem 7. A Trigonometric Composition
For

$$
f(x)=\sin(x^2+1)
$$

compute the derivative. Explicitly identify the outer function, the inner function, and the derivative of the inner function. Finally, determine the sign of $f'(0)$.

> **Why this problem:** it reinforces the chain rule in a different type of composition.

## Solution

The outer function is $g(u)=\sin u$, with $g'(u)=\cos u$. The inner function is $u(x)=x^2+1$, with $u'(x)=2x$.

By the chain rule,

$$
f'(x)=2x\cos(x^2+1).
$$

At zero, $f'(0)=0$: it is neither positive nor negative. The factor $2x$ makes this exact, regardless of $\cos1$.

For a check from the definition, $|\sin(1+h^2)-\sin1|\le h^2$, so the absolute value of the difference quotient at zero is at most $|h|\to0$.
