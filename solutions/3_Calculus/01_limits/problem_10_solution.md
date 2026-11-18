### Exercise 10. Continuity of a Piecewise Function
Find $a$ so that

$$
f(x)=
\begin{cases}
ax+1,&x<2, \\
x^2-1,&x\ge2
\end{cases}
$$

is continuous at $x=2$. Explicitly compare the left-hand limit, right-hand limit, and function value.

> **Why this exercise:** organizes the definition of continuity as agreement among three quantities.

## Solution

The left-hand branch gives

$$
\lim_{x\to2^-}f(x)=2a+1.
$$

The right-hand branch and the actual value give

$$
\lim_{x\to2^+}f(x)=2^2-1=3,\qquad f(2)=3.
$$

Continuity requires all three quantities to agree, so $2a+1=3$ and therefore $a=1$.

For verification at $a=1$, the left limit is $2+1=3$, equal to both the right limit and the function value. Each polynomial branch is continuous on its own side, so the junction is the only condition under consideration.
