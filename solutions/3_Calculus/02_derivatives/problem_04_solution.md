### Problem 4. A Quotient and Domain Control
For

$$
f(x)=\frac{x^2+1}{x-1}
$$

determine the domain, compute the derivative, simplify the result, and explain why the restriction $x\neq1$ remains important.

> **Why this problem:** it practices the quotient rule together with domain control.

## Solution

The denominator excludes $x=1$, so $D_f=\mathbb R\setminus\{1\}$. The quotient rule gives

$$
f'(x)=\frac{2x(x-1)-(x^2+1)}{(x-1)^2}
=\frac{x^2-2x-1}{(x-1)^2},\qquad x\ne1.
$$

The restriction remains because neither the original function nor this derivative is defined at $1$.

For verification, polynomial division gives $f(x)=x+1+2/(x-1)$. Differentiating this form gives $1-2/(x-1)^2$, which equals the stated result.
