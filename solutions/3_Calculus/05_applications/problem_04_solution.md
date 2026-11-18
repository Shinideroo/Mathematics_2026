### Problem 4. Area Between Curves
Find the area of the region bounded by the graphs

$$
y=x
$$

and

$$
y=x^2.
$$

First find the intersection points and justify which function is greater on the relevant interval.

> **Why this problem:** it teaches that before integrating, one must first determine the geometry of the region and the correct order of the functions.

## Solution

Intersections satisfy $x=x^2$, hence $x(x-1)=0$: they are $(0,0)$ and $(1,1)$.

On $[0,1]$, $x-x^2=x(1-x)\ge0$, so the line lies above the parabola. The bounded area is therefore

$$
A=\int_0^1(x-x^2)\,dx
=\left[\frac{x^2}{2}-\frac{x^3}{3}\right]_0^1
=\frac12-\frac13=\frac16.
$$

The difference is nonnegative and vanishes at both intersections, so the unsigned area uses exactly this integrand. For a magnitude check, $0\le x(1-x)\le1/4$ on an interval of length $1$, and $1/6$ is within the resulting bounds.
