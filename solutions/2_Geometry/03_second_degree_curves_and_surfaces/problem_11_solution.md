### Exercise 11. Two Similar Surfaces
Compare

$$
x^2+y^2-z^2=1
$$

and

$$
x^2+y^2-z^2=-1.
$$

For several values $z=c$, check whether the cross-section exists and what its radius is. Based on this, describe qualitatively the difference between the surfaces and make sketches.

> **Why this exercise:** teaches how to recognize the shape of a surface from cross-sections instead of from a memorized catalog of names.

## Solution

Set $z=c$.

For $x^2+y^2-z^2=1$, the section is

$$
x^2+y^2=1+c^2,
$$

a circle of radius $\sqrt{1+c^2}$ for every $c$.

For $x^2+y^2-z^2=-1$, the section is

$$
x^2+y^2=c^2-1.
$$

It is a circle of radius $\sqrt{c^2-1}$ if $|c|>1$, a point if $|c|=1$, and empty if $|c|<1$.

| $c$ | Radius, first surface | Radius, second surface |
| --- | --- | --- |
| $0$ | $1$ | No section |
| $\pm1$ | $\sqrt2$ | $0$ (point) |
| $\pm2$ | $\sqrt5$ | $\sqrt3$ |

The first surface is a connected one-sheet hyperboloid, with its narrowest circular waist at $z=0$. The second is a two-sheet hyperboloid: separate upper and lower parts begin at $(0,0,\pm1)$.

Schematic meridian sketches (rotate each profile around the vertical $z$-axis):

~~~text
One sheet                 Two sheets
 \     /                   \     /
  \   /                     \___/  z=1
   ) (                       gap
  /   \                     /---\  z=-1
 /     \                   /     \
~~~

The computed sections verify the waist versus gap distinction directly.
