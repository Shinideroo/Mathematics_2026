### Problem 5. The Chain Rule as Working Through Layers
For

$$
f(x)=(3x^2-2x+1)^5
$$

identify the inner and outer functions, compute their derivatives, and combine the result according to the chain rule. Explain the origin of the additional factor.

> **Why this problem:** it teaches how to recognize the structure of a composition instead of memorizing the rule as a meaningless pattern.

## Solution

Let the inner function be $u(x)=3x^2-2x+1$ and the outer function be $g(u)=u^5$. Their derivatives are

$$
u'(x)=6x-2,\qquad g'(u)=5u^4.
$$

The chain rule yields

$$
f'(x)=g'(u(x))u'(x)
=5(3x^2-2x+1)^4(6x-2).
$$

The additional factor $6x-2$ measures the rate of change of the inner input; differentiating only the outer power would omit that rate.

As a local check, expanding $(1-2x+3x^2)^5$ gives constant term $1$ and linear term $5(-2x)=-10x$; all remaining terms contain at least $x^2$. Its derivative at zero is therefore $-10$, also obtained by the formula.
