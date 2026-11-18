### Exercise 13. Fundamental Trigonometric Limit
Using

$$
\lim_{x\to0}\frac{\sin x}{x}=1,
$$

compute

$$
\lim_{x\to0}\frac{\sin5x}{x},\qquad \lim_{x\to0}\frac{\sin2x}{\sin3x}.
$$

In each case, show how you reduce the expression to the fundamental limit.

> **Why this exercise:** teaches how to reduce new limits to one known pattern.

## Solution

Angles are in radians. Insert constant factors to produce the fundamental pattern:

$$
\frac{\sin5x}{x}=5\frac{\sin5x}{5x}\longrightarrow5.
$$

For the second limit, near but not at zero,

$$
\frac{\sin2x}{\sin3x}
=\frac23\,\frac{\sin2x/(2x)}{\sin3x/(3x)}
\longrightarrow\frac23\frac11=\frac23.
$$

The fundamental limit applies because $5x$, $2x$, and $3x$ all tend to zero. The latter denominator ratio tends to $1\ne0$, justifying the quotient limit rule. The approximations $\sin(kx)\sim kx$ provide a consistency check on both constant factors.
