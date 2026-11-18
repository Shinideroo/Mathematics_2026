### Problem 12. Symmetry, Sign, and Absolute Value
Compare

$$
\int_{-2}^{2}x\,dx
$$

and

$$
\int_{-2}^{2}|x|\,dx.
$$

Before calculating, predict the results from symmetry and a sketch, then carry out the calculation and explain the difference.

> **Why this problem:** it teaches how to use symmetry and geometry before applying a computational procedure.

## Solution

Before calculation, $y=x$ is odd, so its negative and positive triangular contributions cancel. The graph of $y=|x|$ is a V above the axis, so its two triangle areas add.

~~~text
y=x                     y=|x|
 y                        y
 ^     /                  ^ \     /
 |   /                    |  \   /
 +-/--------> x           +---V-------> x
 /                         -2 0 2
~~~

Calculate:

$$
\int_{-2}^{2}x\,dx
=\left[\frac{x^2}{2}\right]_{-2}^{2}=2-2=0,
$$

$$
\int_{-2}^{2}|x|\,dx
=\int_{-2}^0(-x)\,dx+\int_0^2x\,dx
=2+2=4.
$$

Each triangle has base $2$ and height $2$, hence area $2$, independently checking the results. Absolute value removes cancellation by making the formerly negative part positive.
