### Problem 9. An Oblique Asymptote
Analyze the asymptotes of

$$
f(x)=\frac{x^2+1}{x-1}.
$$

Perform polynomial division and explain why the remainder term vanishes for large $|x|$.

> **Why this problem:** it teaches how to recognize an oblique asymptote and interpret the decomposition of a function.

## Solution

Polynomial division gives

$$
x^2+1=(x-1)(x+1)+2,
\qquad
f(x)=x+1+\frac2{x-1}.
$$

The domain excludes $x=1$. Since $2/(x-1)\to0$ as $x\to\pm\infty$, the oblique asymptote is

$$
y=x+1.
$$

At $x=1$ the numerator is $2\ne0$, so there is also a vertical asymptote $x=1$: the left-hand limit is $-\infty$ and the right-hand limit is $+\infty$. There is no horizontal asymptote because $f(x)$ grows like $x+1$.

The identity $f(x)-(x+1)=2/(x-1)$ verifies the oblique asymptote directly and shows the graph is below it for $x<1$ and above it for $x>1$.
