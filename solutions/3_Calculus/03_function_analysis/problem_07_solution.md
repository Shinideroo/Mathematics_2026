### Problem 7. A Trigonometric Function
On $[0,2\pi]$, find the intervals of monotonicity and the extrema of

$$
f(x)=\sin x+\cos x.
$$

Include the endpoints of the interval and compare the function values at the critical points and at the endpoints.

> **Why this problem:** it practices the analysis of a periodic function on a bounded interval.

## Solution

Differentiate on the interior of the interval:

$$
f'(x)=\cos x-\sin x.
$$

Its zeros in $(0,2\pi)$ are $\pi/4$ and $5\pi/4$. The derivative is positive on $(0,\pi/4)$, negative on $(\pi/4,5\pi/4)$, and positive on $(5\pi/4,2\pi)$.

Thus $f$ increases on $[0,\pi/4]$, decreases on $[\pi/4,5\pi/4]$, and increases on $[5\pi/4,2\pi]$.

| Candidate | Value |
| --- | --- |
| $0$ | $1$ |
| $\pi/4$ | $\sqrt2$ |
| $5\pi/4$ | $-\sqrt2$ |
| $2\pi$ | $1$ |

The global maximum is $\sqrt2$ at $\pi/4$; the global minimum is $-\sqrt2$ at $5\pi/4$. Relative to the closed domain, $0$ is a one-sided local minimum and $2\pi$ a one-sided local maximum, but neither is global.

The identity $f(x)=\sqrt2\sin(x+\pi/4)$ verifies the extremal values and the bounded range.
