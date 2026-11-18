### Exercise 15. Complete Classification of a Line Relative to a Plane
Let

$$
L:p+tv,\qquad \Pi:n\cdot x=d.
$$

State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

> **Why this exercise:** requires formulating a general mathematical criterion instead of carrying out one isolated calculation.

## Solution

For a genuine line and plane, $v\ne0$ and $n\ne0$. Substitute $x=p+tv$ into $n\cdot x=d$:

$$
n\cdot p+t(n\cdot v)=d.
$$

This gives the complete classification:

- If $n\cdot v\ne0$, there is one intersection, at $t=(d-n\cdot p)/(n\cdot v)$.
- If $n\cdot v=0$ and $n\cdot p\ne d$, the line is parallel with no common point.
- If $n\cdot v=0$ and $n\cdot p=d$, the entire line is contained in the plane.

For numerical examples, use $\Pi:z=0$:

1. $(0,0,1)+t(0,0,1)$ meets it once at $t=-1$, namely $(0,0,0)$.
2. $(0,0,1)+t(1,0,0)$ never meets it because $z=1$.
3. $(0,0,0)+t(1,0,0)$ lies in it because $z=0$ for every $t$.

Substitution verifies each example and its distinguishing condition.
