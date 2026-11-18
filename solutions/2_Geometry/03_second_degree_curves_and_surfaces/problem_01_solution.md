### Exercise 1. Recognizing Curves from Canonical Form
Recognize the curves

$$
x^2+y^2=9,
$$

$$
\frac{x^2}{16}+\frac{y^2}{9}=1,
$$

$$
y^2=8x,
$$

$$
\frac{x^2}{9}-\frac{y^2}{4}=1.
$$

For each one, identify the most important features and make a sketch. Explain which parts of the equation let you recognize the type of curve.

> **Why this exercise:** builds the basic dictionary: canonical equation → type of curve → shape and scale.

## Solution

Canonical forms reveal the following curves.

| Equation | Curve | Main features |
| --- | --- | --- |
| $x^2+y^2=9$ | Circle | Center $(0,0)$, radius $3$; intercepts $(\pm3,0),(0,\pm3)$ |
| $x^2/16+y^2/9=1$ | Ellipse | Center $(0,0)$, horizontal semiaxis $4$, vertical semiaxis $3$ |
| $y^2=8x$ | Parabola | Vertex $(0,0)$, symmetry axis $y=0$, opens right; points $(2,\pm4)$ |
| $x^2/9-y^2/4=1$ | Hyperbola | Center $(0,0)$, vertices $(\pm3,0)$, opens left and right; asymptotes $y=\pm2x/3$ |

Equal positive squared coefficients give a circle; unequal positive coefficients give an ellipse; just one squared coordinate gives a parabola; opposite signs give a hyperbola. For example, $y^2=8x$ also has focus $(2,0)$ and directrix $x=-2$ using $y^2=4px$.

Schematic sketches (not to scale; axes cross at the origin):

~~~text
Circle             Ellipse             Parabola            Hyperbola
     y                  y                   y                   y
   .-+-.           .----+----.               |   /           \   |   /
  /  |  \         /     |     \              |  /             ) | (
--+--+--+--x    --+-----+-----+--x         --+<------x      ---)--+--(---x
  \  |  /         \     |     /              |  \             ) | (
   '-+-'           '----+----'               |   \           /   |   \
~~~

In the parabola sketch, the vertex is at the axes' intersection; both branches lie to its right. In the hyperbola sketch, the vertices lie on the horizontal axis and the branches extend outward.

Verification: each listed intercept satisfies its equation. For the hyperbola, $x^2/9-y^2/4=1$ forces $|x|\ge3$, consistent with the outward branches and vertices.
