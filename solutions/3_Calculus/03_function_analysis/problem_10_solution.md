### Problem 10. Complete Function Analysis
Perform a complete analysis of

$$
f(x)=\frac{x}{x^2+1}.
$$

Include the domain, symmetry, zeros, limits, monotonicity, extrema, and convexity. Finally, produce a sketch based only on this information.

> **Why this problem:** it combines all the basic elements of function analysis into one organized process.

## Solution

The denominator is always positive, so the domain is $\mathbb R$. The function is odd, because $f(-x)=-f(x)$, and its only zero is $x=0$. It is negative on the negative axis and positive on the positive axis.

The limits are $f(x)\to0^-$ as $x\to-\infty$ and $f(x)\to0^+$ as $x\to+\infty$. Thus $y=0$ is the horizontal asymptote; there are no vertical asymptotes.

Differentiate:

$$
f'(x)=\frac{1-x^2}{(x^2+1)^2}.
$$

It is negative on $(-\infty,-1)$ and $(1,\infty)$ and positive on $(-1,1)$. Hence the global minimum is $(-1,-1/2)$ and global maximum is $(1,1/2)$.

A second differentiation gives

$$
f''(x)=\frac{2x(x^2-3)}{(x^2+1)^3}.
$$

| Interval | Sign of $f''$ | Curvature |
| --- | --- | --- |
| $(-\infty,-\sqrt3)$ | $-$ | Concave down |
| $(-\sqrt3,0)$ | $+$ | Convex (concave up) |
| $(0,\sqrt3)$ | $-$ | Concave down |
| $(\sqrt3,\infty)$ | $+$ | Convex (concave up) |

The inflection points are $(-\sqrt3,-\sqrt3/4)$, $(0,0)$, and $(\sqrt3,\sqrt3/4)$.

~~~text
y
                                |
                                |     o
                                |   ********
                                |  **      o****
                                | **           *****
                                | *                ********
                                |**                       *******
                                |*
                                **
--------------------------------o--------------------------------
                               **
                               *|
*******                       **|
      ********                * |
             *****           ** |
                 ****o      **  |
                     ********   |
                          o     |
                                |
x: -5 to 5; y: -0.6 to 0.6
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The left tail approaches zero from below and the right tail from above; mark the additional inflections at $x=\pm\sqrt3$. For verification of the global bounds, $2|x|\le x^2+1$ implies $|f(x)|\le1/2$, with equality exactly at $x=\pm1$.
