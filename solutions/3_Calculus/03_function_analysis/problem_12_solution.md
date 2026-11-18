### Problem 12. A Function with an Absolute Value
Analyze

$$
f(x)=|x^2-4|.
$$

First sketch $x^2-4$, then explain the effect of the absolute value. Indicate the points where the derivative does not exist and justify the reason geometrically.

> **Why this problem:** it shows the limits of mechanical application of calculus and the importance of the geometry of the graph.

## Solution

Start with the upward parabola $x^2-4$, with vertex $(0,-4)$ and zeros $\pm2$. Taking absolute value reflects its part below the horizontal axis upward:

$$
f(x)=
\begin{cases}
x^2-4,&|x|\ge2,\\
4-x^2,&|x|<2.
\end{cases}
$$

The domain is $\mathbb R$, the function is even and nonnegative, and the zeros $(\pm2,0)$ are global minima. On the smooth pieces,

$$
f'(x)=
\begin{cases}
2x,&|x|>2,\\
-2x,&|x|<2.
\end{cases}
$$

It decreases on $(-\infty,-2)$, increases on $(-2,0)$, decreases on $(0,2)$, and increases on $(2,\infty)$. The central point $(0,4)$ is a local maximum.

At $x=-2$, the left and right slopes are $-4$ and $4$. At $x=2$, they are $-4$ and $4$ again. Thus the function is continuous but not differentiable at $\pm2$, where the reflected arcs form sharp corners.

~~~text
Original: y=x^2-4
y
                                |
                                |
**                              |                              **
 **                             |                             **
  **                            |                            **
   ***                          |                          ***
     **                         |                         **
      **                        |                        **
       ***                      |                      ***
         **                     |                     **
----------*o*-------------------+-------------------*o*----------
            ***                 |                 ***
              ***               |               ***
                ***             |             ***
                  ****          |          ****
                     ****       |       ****
                        ********o********
                                |
                                |
x: -3 to 3; y: -5 to 6
* = curve; o = marked point; horizontal/vertical lines = axes

After reflection: y=|x^2-4|
y
                                |
                                |
                                |
**                              |                              **
 *                              |                              *
 **                         ****o****                         **
  **                    *****   |   *****                    **
   **                 ***       |       ***                 **
    *               ***         |         ***               *
    **            ***           |           ***            **
     **          **             |             **          **
      **       ***              |              ***       **
       **     **                |                **     **
        **   **                 |                 **   **
         ** **                  |                  ** **
----------*o*-------------------+-------------------*o*----------
                                |
                                |
                                |
x: -3 to 3; y: -1 to 6
* = curve; o = marked point; horizontal/vertical lines = axes
~~~

The second sketch shows two zero-height corners joined by the downward arch $4-x^2$, with upward outer arms. Substitution at $0,\pm2$ verifies the marked heights.
