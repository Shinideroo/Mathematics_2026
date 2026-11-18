### Exercise 15. Recognition and Sketch Without a Given Name
Consider the two equations:

$$
4x^2+9y^2-8x+36y+4=0,
$$

$$
4x^2+y^2=z^2.
$$

For the first equation, reduce it to canonical form, recognize the curve, give its most important features, and make a sketch.

For the second equation, do not begin by using a ready-made name for the surface. First describe the cross-sections $z=c$ and the cross-sections by the planes $x=0$ and $y=0$, paying attention to the different scales along the axes. Only then identify the surface and make a sketch.

> **Why this exercise:** tests transfer of the two main mechanisms of the set—moving to canonical form and recognizing an object through cross-sections—without allowing the easiest example to be chosen.

## Solution

**First equation.** Complete the squares:

$$
4[(x-1)^2-1]+9[(y+2)^2-4]+4=0,
$$

so

$$
4(x-1)^2+9(y+2)^2=36,
\qquad
\frac{(x-1)^2}{9}+\frac{(y+2)^2}{4}=1.
$$

This is an ellipse centered at $(1,-2)$, with horizontal semiaxis $3$ and vertical semiaxis $2$. Its horizontal vertices are $(-2,-2),(4,-2)$; its vertical vertices are $(1,0),(1,-4)$.

~~~text
             (1,0)
           .---*---.
         /     |     \
(-2,-2) *----center---* (4,-2)
         \     |     /
           '---*---'
             (1,-4)
~~~

For verification, $(4,-2)$ gives $64+36-32-72+4=0$ in the original equation.

**Second equation.** First examine the sections of $4x^2+y^2=z^2$.

At $z=c\ne0$,

$$
\frac{x^2}{c^2/4}+\frac{y^2}{c^2}=1.
$$

These are ellipses with semiaxes $|c|/2$ along $x$ and $|c|$ along $y$. At $c=0$, the section is the origin. At $x=0$, the section is $y=\pm z$; at $y=0$, it is $z=\pm2x$.

These sections identify a double elliptic cone with vertex at the origin and axis $Oz$, twice as wide in the $y$ direction as in the $x$ direction at any fixed nonzero height.

~~~text
Axial profile in xz        Axial profile in yz
     \ /                       \   /
      O                         \ /
     / \                         O
                                / \
(narrower in x)             (wider in y)
~~~

At $z=2$, the section intercepts are $(\pm1,0,2)$ and $(0,\pm2,2)$, which all satisfy the equation and verify the different scales.
