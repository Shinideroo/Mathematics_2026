### Problem 3. The Product Rule — Why Is It Needed?
For

$$
f(x)=(x^2+1)e^x
$$

compute the derivative. Then compare the correct result with the incorrect idea

$$
f'(x)\stackrel{?}{=}(2x)e^x
$$

and explain which term is missing.

> **Why this problem:** it teaches the product rule by analyzing a common mistake.

## Solution

Both factors depend on $x$, so use $(uv)'=u'v+uv'$:

$$
f'(x)=2xe^x+(x^2+1)e^x
=e^x(x^2+2x+1)=e^x(x+1)^2.
$$

The proposed incorrect expression retains only the derivative of the first factor times the unchanged second factor. It omits $(x^2+1)e^x$, the contribution from differentiating $e^x$.

For a check, at $x=0$ the correct derivative is $1$, whereas the incorrect expression gives $0$. Directly, $f(h)=e^h+h^2e^h$, so $(f(h)-f(0))/h=(e^h-1)/h+he^h\to1$, verifying the correct value.
