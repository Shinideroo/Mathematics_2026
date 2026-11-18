### Problem 8. Choosing the Factors in Integration by Parts
Compute

$$
\int x\cos x\,dx.
$$

Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

> **Why this problem:** it teaches that integration by parts requires a deliberate choice of factors.

## Solution

Choose $u=x$, $dv=\cos x\,dx$, giving $du=dx$, $v=\sin x$. Differentiating $x$ reduces it to $1$, leaving an elementary integral. Reversing the roles would introduce $x^2/2$ and a more complicated polynomial-trigonometric product.

Integration by parts gives

$$
\int x\cos x\,dx=x\sin x-\int\sin x\,dx
=x\sin x+\cos x+C.
$$

Check:

$$
(x\sin x+\cos x+C)'=\sin x+x\cos x-\sin x=x\cos x.
$$
