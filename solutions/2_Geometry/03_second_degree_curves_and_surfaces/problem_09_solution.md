### Exercise 9. Ellipsoid and Its Cross-Sections
Consider

$$
\frac{x^2}{9}+\frac{y^2}{4}+\frac{z^2}{16}=1.
$$

Give the semiaxis lengths, describe the cross-section $z=0$, and explain how the cross-sections $z=c$ change for $|c|<4$.

> **Why this exercise:** teaches how to understand a 3D surface through a family of simpler 2D cross-sections.

## Solution

The ellipsoid has semiaxis lengths $3$, $2$, and $4$ along $Ox$, $Oy$, and $Oz$, respectively.

At $z=0$, its cross-section is the ellipse $x^2/9+y^2/4=1$ in that plane.

For $z=c$, put $q=1-c^2/16$. The section satisfies

$$
\frac{x^2}{9}+\frac{y^2}{4}=q.
$$

If $|c|<4$, then $q>0$ and the section is an ellipse centered at $(0,0,c)$, with semiaxes $3\sqrt q$ and $2\sqrt q$. Sections are widest at $c=0$, shrink as $|c|$ increases, and are identical in size at $c$ and $-c$.

At $|c|=4$ the section is one point; for $|c|>4$ it is empty. For verification, $(3\sqrt q,0,c)$ gives $q+c^2/16=1$ in the original equation.
