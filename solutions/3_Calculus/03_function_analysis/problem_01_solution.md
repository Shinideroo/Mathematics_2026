### Problem 1. A Cubic Polynomial
Analyze the monotonicity and extrema of

$$
f(x)=x^3-3x^2+2.
$$

Sketch the graph based on the results and mark the critical points.

> **Why this problem:** it teaches how to use the first derivative to describe the shape of a polynomial.

## Solution

The domain is $\mathbb R$. Differentiate and factor:

$$
f'(x)=3x^2-6x=3x(x-2).
$$

| $x$ | $(-\infty,0)$ | $0$ | $(0,2)$ | $2$ | $(2,\infty)$ |
| --- | --- | --- | --- | --- | --- |
| Sign of $f'$ | $+$ | $0$ | $-$ | $0$ | $+$ |
| Behavior | Increasing | Local maximum | Decreasing | Local minimum | Increasing |

The critical points are $(0,2)$ and $(2,-2)$. Neither is a global extremum, since the cubic tends to $-\infty$ on the left and $+\infty$ on the right.

For a more precise sketch, $f''(x)=6x-6$ gives inflection point $(1,0)$. Also

$$
f(x)=(x-1)(x^2-2x-2),
$$

so its zeros are $1-\sqrt3$, $1$, and $1+\sqrt3$.

~~~text
y
                   |                                        *
                   |                                       **
                   |                                       *
                   |                                      **
                   |                                      *
               ****o******                               **
             ***   |     ***                            **
           ***     |       ***                         **
          **       |         ***                       *
---------**--------+-----------*o*--------------------**---------
         *         |             ***                 **
        **         |               ***             ***
       **          |                 ***         ***
      **           |                   ***********
      *            |                         o
     **            |
     *             |
    **             |
    *              |
x: -1.5 to 3.5; y: -4 to 4
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The essential shape is rise to $(0,2)$, fall through $(1,0)$ to $(2,-2)$, then rise without bound. Test values $f'(-1)=9$, $f'(1)=-3$, and $f'(3)=9$ verify the sign chart.
