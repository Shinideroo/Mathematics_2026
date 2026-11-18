### Exercise 5. Hyperbola and Asymptotes
For

$$
\frac{x^2}{16}-\frac{y^2}{9}=1,
$$

find the intercepts with the $x$-axis, the asymptotes, and make a sketch. Explain why the asymptotes describe the behavior of the curve far from the center.

> **Why this exercise:** shows the role of asymptotes in understanding the global shape of a hyperbola.

## Solution

Set $y=0$: $x^2/16=1$, so the vertices and $x$-axis intercepts are $(\pm4,0)$.

For the asymptotes, set the quadratic part equal to zero:

$$
\frac{x^2}{16}-\frac{y^2}{9}=0
\quad\Longrightarrow\quad y=\pm\frac34x.
$$

The actual branches satisfy

$$
y=\pm\frac34\sqrt{x^2-16},\qquad |x|\ge4.
$$

To verify approach to the asymptote lines,

$$
\left||y|-\frac34|x|\right|
=\frac{12}{|x|+\sqrt{x^2-16}}\longrightarrow0.
$$

Thus far from the center each arm approaches one of the two lines.

~~~text
              y
              ^
   \          |          /
    \         |         /
     )        |        (
------*-------O-------*---------> x
     )        |        (
    /         |         \
   /          |          \
   vertex (-4,0)   vertex (4,0)
~~~

The branches open left and right from the two vertices; the asymptotes are the lines of slopes $\pm3/4$ through $O$. Direct substitution of $(\pm4,0)$ gives $1$.
