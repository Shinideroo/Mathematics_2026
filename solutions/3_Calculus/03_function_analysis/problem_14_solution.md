### Problem 14. Reconstructing Information from the Derivative
It is known that

$$
f'(x)=(x-1)(x+2).
$$

Determine the monotonicity and the locations of the extrema, and sketch a possible qualitative shape of the function. Then, for

$$
g(x)=\frac{x^3}{3}+\frac{x^2}{2}-2x
$$

verify that $g'(x)=(x-1)(x+2)$, and compare the specific graph with the earlier qualitative sketch.

> **Why this problem:** it teaches how to read the behavior of a function directly from its derivative.

## Solution

Use the factors of the given derivative:

| $x$ | $(-\infty,-2)$ | $-2$ | $(-2,1)$ | $1$ | $(1,\infty)$ |
| --- | --- | --- | --- | --- | --- |
| Sign of $f'$ | $+$ | $0$ | $-$ | $0$ | $+$ |

Therefore $f$ increases before $-2$, decreases between $-2$ and $1$, and increases after $1$. It has a local maximum at $x=-2$ and local minimum at $x=1$. Their heights cannot be fixed from the derivative alone.

For the specified polynomial,

$$
g'(x)=x^2+x-2=(x-1)(x+2).
$$

Its critical values are $g(-2)=10/3$ and $g(1)=-7/6$.

~~~text
y
                                     |                       *
                                     |                       *
                                     |                      **
                                     |                      *
              ****o*****             |                     **
            ***        ****          |                    **
           **             ***        |                    *
          **                ***      |                   **
         **                   **     |                  **
        **                     ***   |                 **
       **                        *** |                **
------**---------------------------***---------------**----------
     **                              ***           ***
     *                               | *****     ***
    **                               |     ***o***
    *                                |
   **                                |
   *                                 |
  **                                 |
x: -4 to 3; y: -3 to 5
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The sketch shows rise, fall, rise. More precisely, the graph follows $(-\infty,-\infty)\nearrow(-2,10/3)\searrow(1,-7/6)\nearrow(+\infty,+\infty)$.

Every differentiable function on $\mathbb R$ with this derivative differs from $g$ by a constant, so it has the same shape shifted vertically. Expanding the factored derivative verifies the comparison.
