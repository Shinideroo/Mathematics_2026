### Problem 11. Volume of a Solid of Revolution
The region under the graph

$$
y=\sqrt{x},\qquad x\in[0,4],
$$

is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

> **Why this problem:** it teaches how to construct an integral from the geometry of cross-sections instead of applying a volume formula without understanding its origin.

## Solution

A slice perpendicular to the $x$-axis is a disk with radius $y=\sqrt x$. Its area is $\pi y^2=\pi x$. Summing these areas times their thickness gives

$$
V=\int_0^4\pi(\sqrt x)^2\,dx
=\pi\int_0^4x\,dx
=\pi\left[\frac{x^2}{2}\right]_0^4
=8\pi.
$$

Thus the volume is $8\pi$ cubic units.

The factor $\pi y^2$ comes from the ordinary area formula for a circle, with the graph height as disk radius. As a check, the disk area increases linearly from $0$ to $4\pi$, so its average is $2\pi$; multiplying by the length $4$ gives $8\pi$ again.
