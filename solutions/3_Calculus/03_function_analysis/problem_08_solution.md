### Problem 8. The Second Derivative
For

$$
f(x)=x^4-4x^2
$$

find the local extrema, intervals of convexity and concavity, and inflection points. Sketch the graph and mark all the identified features on it.

> **Why this problem:** it introduces the second derivative as a tool for describing the curvature of a graph.

## Solution

The derivatives are

$$
f'(x)=4x(x^2-2),\qquad f''(x)=12x^2-8.
$$

The critical points are $x=-\sqrt2,0,\sqrt2$. The sign of $f'$ is $-,+,-,+$ on the successive intervals they determine. Hence the local minima are $(\pm\sqrt2,-4)$, both global; the local maximum is $(0,0)$.

The second derivative vanishes at $x=\pm\sqrt{2/3}$. It is positive outside these points and negative between them. Therefore:

- Convex (concave up): $(-\infty,-\sqrt{2/3})$ and $(\sqrt{2/3},\infty)$.
- Concave down: $(-\sqrt{2/3},\sqrt{2/3})$.
- Inflection points: $(\pm\sqrt{2/3},-20/9)$.

The even function has zeros $-2,0,2$ and tends to $+\infty$ at both ends.

~~~text
y
  *                             |                             *
  **                            |                            **
   *                            |                            *
   *                            |                            *
   **                           |                           **
    *                           |                           *
    *                           |                           *
    **                          |                          **
     *                          |                          *
-----**---------------------****o****---------------------**-----
      *                   ***   |   ***                   *
      **                ***     |     ***                **
       *              ***       |       ***              *
       **           *o*         |         *o*           **
        **        ***           |           ***        **
         **     ***             |             ***     **
          ***o***               |               ***o***
                                |
                                |
x: -2.4 to 2.4; y: -5 to 5
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The schematic is a symmetric W: the inflections lie between each minimum and the central maximum. As a check, $f(x)=(x^2-2)^2-4\ge-4$, confirming both global minima.
