### Problem 3. A Box Made from Cardboard
From a $30\,\mathrm{cm}\times40\,\mathrm{cm}$ sheet, squares of side length $x$ are cut from the corners and the edges are folded up to form an open box.

Write the volume as a function of $x$, determine the physically meaningful domain, and find the value of $x$ for which the volume is greatest.

> **Why this problem:** it develops optimization modeling in a situation where the objective function is not given and must be built independently from the geometry.

## Solution

After cutting squares, the box dimensions are $x$, $30-2x$, and $40-2x$ centimeters. Thus

$$
V(x)=x(30-2x)(40-2x)
=1200x-140x^2+4x^3,
\qquad 0<x<15.
$$

All three lengths must be positive. Differentiate:

$$
V'(x)=1200-280x+12x^2=4(3x^2-70x+300).
$$

The critical values are

$$
x=\frac{70\pm\sqrt{4900-3600}}6
=\frac{35\pm5\sqrt{13}}3.
$$

Only

$$
x_*=\frac{35-5\sqrt{13}}3\approx5.6574\ \mathrm{cm}
$$

lies in the domain; the other root exceeds $15$. The derivative is positive before $x_*$ and negative afterward up to $15$, so this is the global maximum. The continuous extension has $V(0)=V(15)=0$, confirming that neither degenerate boundary can improve it.

At the optimum,

$$
V_{\max}=\frac{35000+13000\sqrt{13}}{27}
\approx3032.30\ \mathrm{cm}^3.
$$

As a second check, $V''(x_*)=24x_*-280=-40\sqrt{13}<0$. The remaining side lengths are positive (approximately $18.6852$ and $28.6852$ cm), verifying physical feasibility.
