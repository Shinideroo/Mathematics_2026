### Problem 6. Average Value of a Function
Compute the average value of the function

$$
f(x)=x^2
$$

on the interval $[0,3]$.

Find a point $c\in[0,3]$ for which $f(c)$ is equal to this average value, and interpret the result geometrically.

> **Why this problem:** it gives the integral the interpretation of an average value and connects the numerical result with a level of the function on the graph.

## Solution

The average value over an interval is its integral divided by the interval length:

$$
f_{\mathrm{avg}}=\frac1{3-0}\int_0^3x^2\,dx
=\frac13\left[\frac{x^3}{3}\right]_0^3=3.
$$

To find $c$, solve $c^2=3$ with $c\in[0,3]$. The permitted point is $c=\sqrt3$.

Geometrically, the rectangle of width $3$ and height $3$ has area $9$, equal to the area under $y=x^2$ on $[0,3]$. This checks the average, and $f(\sqrt3)=3$ checks the chosen point. Continuity guarantees such a point by the integral mean-value theorem.
