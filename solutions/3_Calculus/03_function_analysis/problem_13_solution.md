### Problem 13. A Logarithm and an Asymptote
Perform a complete analysis of

$$
f(x)=\frac{\ln x}{x},\qquad x>0.
$$

Find the maximum and the behavior at the ends of the domain. Explain which information is necessary for a correct sketch.

> **Why this problem:** it combines the domain, limits, and derivative in a less obvious example.

## Solution

The domain is $(0,\infty)$. The zero is $x=1$; $f$ is negative on $(0,1)$ and positive on $(1,\infty)$.

At the ends of the domain,

$$
\lim_{x\to0^+}\frac{\ln x}{x}=-\infty,\qquad
\lim_{x\to+\infty}\frac{\ln x}{x}=0^+.
$$

For the first, set $x=e^{-u}$ to obtain $-ue^u\to-\infty$; for the second, logarithmic growth is slower than linear growth. Thus $x=0$ is a vertical asymptote and $y=0$ a right-hand horizontal asymptote.

Differentiate:

$$
f'(x)=\frac{1-\ln x}{x^2}.
$$

The function increases on $(0,e)$ and decreases on $(e,\infty)$. Its global maximum is $(e,1/e)$; there is no minimum.

For curvature,

$$
f''(x)=\frac{2\ln x-3}{x^3}.
$$

It is concave down on $(0,e^{3/2})$ and convex on $(e^{3/2},\infty)$, with inflection point $(e^{3/2},3/(2e^{3/2}))$.

~~~text
y
|
|
|         *******o***********************
|       ***                             *************************
|      **
|      *
+-----o*---------------------------------------------------------
|     *
|    **
|    *
|    *
|    *
|   **
|   *
|   *
|   *
|   *
|   *
|   *
x: 0 to 10; y: -1 to 0.5
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

A correct sketch needs the positive domain, the two end limits, the zero, and the maximum; curvature locates the change in bending. Substituting $x=e$ in $f'$ gives zero and in $f''$ gives $-1/e^3<0$, verifying the maximum.
