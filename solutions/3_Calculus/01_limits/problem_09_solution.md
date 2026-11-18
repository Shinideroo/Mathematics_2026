### Exercise 9. One-Sided Limits and an Asymptote
Analyze the left-hand and right-hand limits of

$$
f(x)=\frac1{x-2}
$$

as $x\to2$. Does the two-sided limit exist? Interpret the result on a sketch of the graph and identify the vertical asymptote.

> **Why this exercise:** teaches how to distinguish one-sided limits and connect them with the geometry of an asymptote.

## Solution

If $x<2$, the denominator approaches zero through negative values; if $x>2$, it approaches through positive values. Hence

$$
\lim_{x\to2^-}\frac1{x-2}=-\infty,\qquad
\lim_{x\to2^+}\frac1{x-2}=+\infty.
$$

The one-sided limits disagree, so no two-sided limit exists, even as a single extended-real value. The vertical asymptote is $x=2$; the horizontal asymptote is $y=0$.

~~~text
 y
 ^          :\
 |          : \
 |          :  \____
 +----------:--------------> x
 | ____     : x=2
 |     \    :
 |      \   :
 |       \  :
~~~

For a sign check, $f(1.9)=-10$ and $f(2.1)=10$; moving closer to $2$ increases their magnitudes.
