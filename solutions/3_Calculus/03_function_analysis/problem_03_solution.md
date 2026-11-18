### Problem 3. A Rational Function
Analyze the domain, zeros, asymptotes, and monotonicity of

$$
f(x)=\frac{x+1}{x-2}.
$$

Finally, sketch a graph consistent with all the information obtained.

> **Why this problem:** it teaches how to combine the domain, limits, and derivative in the analysis of a rational function.

## Solution

Rewrite

$$
f(x)=1+\frac3{x-2}.
$$

The domain is $\mathbb R\setminus\{2\}$, the zero is $x=-1$, and $f(0)=-1/2$.

Limits give

$$
\lim_{x\to2^-}f(x)=-\infty,\quad
\lim_{x\to2^+}f(x)=+\infty,\quad
\lim_{x\to\pm\infty}f(x)=1.
$$

Thus the asymptotes are $x=2$ and $y=1$. Moreover,

$$
f'(x)=-\frac3{(x-2)^2}<0,
$$

so each branch is strictly decreasing on $(-\infty,2)$ or $(2,\infty)$, with no extrema. It is positive on $(-\infty,-1)$ and $(2,\infty)$, and negative on $(-1,2)$.

~~~text
y
                       |          *
                       |          **
                       |           *
                       |           **
                       |            **
                       |             **
                       |              ***
                       |                *******
                       |                      *******************
                       |
*******************    |
------------------o******----------------------------------------
                       |***
                       |  **
                       |   **
                       |    **
                       |     *
                       |     **
                       |      *
x: -5 to 9; y: -5 to 7
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The left branch lies below $y=1$ and crosses at $(-1,0)$; the right branch lies above it. The identity $(x-2)(f(x)-1)=3$ verifies the asymptote placement and branch sides.
