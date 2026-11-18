### Problem 11. A Parameter and the Number of Extrema
For

$$
f_a(x)=x^3-3ax
$$

depending on $a$, determine the number of critical points and their character. Separate the parameter cases and justify why the structure of the graph changes.

> **Why this problem:** it teaches how to analyze an entire family of functions instead of a single example.

## Solution

Differentiate:

$$
f_a'(x)=3(x^2-a).
$$

- If $a>0$, there are two critical points $x=\pm\sqrt a$. The derivative is positive outside and negative between them. Thus $(-\sqrt a,2a^{3/2})$ is a local maximum and $(\sqrt a,-2a^{3/2})$ a local minimum.
- If $a=0$, the only critical point is $x=0$. The function is $x^3$, strictly increasing, so the point is a stationary inflection, not an extremum.
- If $a<0$, $x^2-a>0$ everywhere: there are no critical points and the function is strictly increasing.

Verification for $a>0$: $f_a''(x)=6x$ is negative at $-\sqrt a$ and positive at $\sqrt a$, agreeing with the classification. The graph changes because the equation $x^2=a$ has two, one, or no real roots as $a$ passes through zero.
