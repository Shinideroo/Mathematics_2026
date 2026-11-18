### Problem 6. A Logarithmic Function
Analyze the domain, zero, and monotonicity of

$$
f(x)=\ln x-x+1.
$$

Explain why the analysis must begin with the domain.

> **Why this problem:** it reinforces the role of the domain and derivative in the analysis of a logarithmic function.

## Solution

Start with the domain $x>0$, since $\ln x$ is not real for $x\le0$. Differentiate only on this domain:

$$
f'(x)=\frac1x-1=\frac{1-x}{x}.
$$

It is positive on $(0,1)$ and negative on $(1,\infty)$. Hence $f$ increases to its global maximum $f(1)=0$ and decreases afterward. Its unique zero is $x=1$.

For verification, $f''(x)=-1/x^2<0$, so the graph is strictly concave, confirming the maximum. Also $f(x)\to-\infty$ at both $0^+$ and $+\infty$. The domain must come first so that no derivative sign or limit argument is assigned to points where the logarithm is undefined.
