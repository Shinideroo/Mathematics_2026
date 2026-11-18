### Problem 12. Several Rules at Once
For

$$
f(x)=(x^2+1)^3e^x
$$

compute the derivative. Before calculating, write down a plan: which rule applies to the whole expression and which rule applies to one of its factors. Finally, organize the result by factoring out common factors.

> **Why this problem:** it practices the order of decisions when combining familiar differentiation rules.

## Solution

Plan: the whole expression is a product, so apply the product rule. Its first factor is a composition, so differentiate that factor by the chain rule.

$$
f'(x)=3(x^2+1)^2(2x)e^x+(x^2+1)^3e^x.
$$

Factor common terms:

$$
f'(x)=e^x(x^2+1)^2\bigl(6x+x^2+1\bigr).
$$

Thus the organized result is $e^x(x^2+1)^2(x^2+6x+1)$.

As a check, $f(x)>0$, so logarithmic differentiation gives $f'/f=6x/(x^2+1)+1$. Multiplying by $f$ reproduces the same factored derivative.
