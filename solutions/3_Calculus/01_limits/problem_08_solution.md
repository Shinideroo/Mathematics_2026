### Exercise 8. A Square Root in a Function Limit
Compute

$$
\lim_{x\to4}\frac{\sqrt{x}-2}{x-4}
$$

by rationalizing the numerator. Compare the idea with Exercise 3 involving a sequence.

> **Why this exercise:** reinforces transferring the same algebraic technique between two types of limits.

## Solution

Multiply numerator and denominator by $\sqrt x+2$. For $x\ne4$,

$$
\frac{\sqrt x-2}{x-4}
=\frac{x-4}{(x-4)(\sqrt x+2)}
=\frac1{\sqrt x+2}.
$$

Thus the limit is $1/(2+2)=1/4$.

As in Exercise 3, conjugation uses a difference of squares to remove the troublesome subtraction. Here it removes a $0/0$ form at a finite point rather than an $\infty-\infty$ form at infinity. The simplified expression is continuous near $4$, verifying the use of direct substitution after cancellation.
