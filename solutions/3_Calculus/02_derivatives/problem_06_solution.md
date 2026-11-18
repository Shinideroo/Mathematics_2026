### Problem 6. Product Rule and Trigonometry
For

$$
f(x)=x\sin x+\cos x
$$

compute the derivative and simplify the result. Then compute $f'(0)$ and interpret the direction of the tangent line at that point.

> **Why this problem:** it combines the product rule with trigonometric derivatives and geometric interpretation.

## Solution

Differentiate $x\sin x$ by the product rule and $\cos x$ directly:

$$
f'(x)=\sin x+x\cos x-\sin x=x\cos x.
$$

Hence $f'(0)=0$, so the tangent is horizontal. Since $f(0)=1$, its equation is $y=1$.

For verification, the difference quotient at zero is $\sin h+(\cos h-1)/h$. Its first term tends to zero, and $|(\cos h-1)/h|=2\sin^2(h/2)/|h|\le |h|/2\to0$. Thus the quotient tends to $0$, agreeing with the derivative.
