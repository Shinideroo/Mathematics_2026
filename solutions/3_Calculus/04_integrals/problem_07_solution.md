### Problem 7. Integration by Parts as Reversing the Product Rule
Compute

$$
\int xe^x\,dx.
$$

First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

> **Why this problem:** it connects a new technique with the familiar product rule.

## Solution

The product rule is $(uv)'=u'v+uv'$. Integrating and rearranging gives the integration-by-parts formula

$$
\int u\,dv=uv-\int v\,du.
$$

It transfers differentiation from one factor to the other. Choose $u=x$ and $dv=e^x\,dx$, so $du=dx$ and $v=e^x$. Then

$$
\int xe^x\,dx=xe^x-\int e^x\,dx=(x-1)e^x+C.
$$

Verification by the product rule:

$$
\frac{d}{dx}\bigl((x-1)e^x+C\bigr)
=e^x+(x-1)e^x=xe^x.
$$
