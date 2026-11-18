### Problem 4. A Function with Two Vertical Asymptotes
Analyze

$$
f(x)=\frac1{x^2-1}.
$$

Determine the domain, asymptotes, sign, and monotonicity on the intervals of the domain. Explain why each interval must be analyzed separately.

> **Why this problem:** it practices the analysis of a function on several disjoint intervals.

## Solution

The denominator vanishes at $\pm1$, so $D_f=\mathbb R\setminus\{-1,1\}$. The function is positive for $|x|>1$ and negative for $|x|<1$; it has no zero.

Its vertical asymptotes are $x=-1$ and $x=1$, with

$$
f(-1^-)=+\infty,\quad f(-1^+)=-\infty,\quad
f(1^-)=-\infty,\quad f(1^+)=+\infty,
$$

where these expressions denote one-sided limits. Since $f(x)\to0^+$ as $x\to\pm\infty$, $y=0$ is horizontal.

Differentiate:

$$
f'(x)=-\frac{2x}{(x^2-1)^2}.
$$

Thus it increases on $(-\infty,-1)$ and $(-1,0)$, and decreases on $(0,1)$ and $(1,\infty)$. There is a local maximum at $(0,-1)$, but no global maximum or minimum.

The excluded points split the domain, so increasing behavior cannot be asserted across an asymptote. For example, $-2<0$ but $f(-2)=1/3>f(0)=-1$, demonstrating why the intervals must be separated.
