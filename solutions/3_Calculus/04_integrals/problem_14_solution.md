### Problem 14. A Piecewise-Defined Function
Let

$$
f(x)=
\begin{cases}
x+1,&-1\le x<1, \\
2,&1\le x\le3.
\end{cases}
$$

Sketch the graph, decide where to split the integral, compute

$$
\int_{-1}^{3}f(x)\,dx
$$

and verify the result geometrically.

> **Why this problem:** it requires understanding the definition of the function before carrying out the calculation.

## Solution

The graph is the segment from $(-1,0)$ to $(1,2)$, followed by the horizontal segment from $(1,2)$ to $(3,2)$. Both formulas give height $2$ at the junction, although the first branch excludes that endpoint.

~~~text
 y
2|        *---------*
 |      /           |
 |    /             |
0+--*----------------------> x
   -1     1         3
~~~

Split at $x=1$, where the formula changes:

$$
\int_{-1}^{3}f(x)\,dx
=\int_{-1}^{1}(x+1)\,dx+\int_1^3 2\,dx
=\left[\frac{x^2}{2}+x\right]_{-1}^{1}+[2x]_1^3
=2+4=6.
$$

Geometrically, the first part is a triangle of base $2$ and height $2$, area $2$; the second is a rectangle of width $2$ and height $2$, area $4$. Their sum $6$ verifies the integration.
