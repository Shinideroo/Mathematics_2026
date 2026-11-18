### Exercise 10. Paraboloids
Compare

$$
z=x^2+y^2
$$

and

$$
z=x^2-y^2.
$$

For each surface, describe the cross-sections $x=0$, $y=0$, and $z=c$, then make a qualitative sketch.

> **Why this exercise:** teaches how to distinguish two basic types of paraboloids from their cross-sections.

## Solution

**For $z=x^2+y^2$:**

- $x=0$: $z=y^2$, an upward parabola.
- $y=0$: $z=x^2$, an upward parabola.
- $z=c$: $x^2+y^2=c$, a circle of radius $\sqrt c$ for $c>0$, the origin for $c=0$, and no points for $c<0$.

It is an elliptic (here circular) paraboloid opening upward.

**For $z=x^2-y^2$:**

- $x=0$: $z=-y^2$, a downward parabola.
- $y=0$: $z=x^2$, an upward parabola.
- $z=c$: $x^2-y^2=c$. If $c>0$ it is a hyperbola opening along $x$; if $c<0$ it opens along $y$; at $c=0$ it is the two lines $y=\pm x$.

It is a hyperbolic paraboloid, or saddle.

Qualitative sketches via perpendicular vertical profiles (horizontal axes show the indicated coordinate):

~~~text
Circular paraboloid:         Saddle:
x-profile     y-profile     x-profile     y-profile
 \     /       \     /       \     /       /-----\
  \___/         \___/         \___/       /       \
   z>=0          z>=0       rises in x    falls in y
~~~

For an algebraic check of the contrast, both surfaces give $z=1$ at $(x,y)=(1,0)$, but at $(0,1)$ their heights are $1$ and $-1$. Thus the first is a bowl while the second bends in opposite directions.
