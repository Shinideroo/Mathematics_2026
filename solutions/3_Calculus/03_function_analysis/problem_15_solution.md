### Problem 15. Find the Error in the Monotonicity Analysis
For the function

$$
f(x)=x^3-3x
$$

the derivative was correctly computed as

$$
f'(x)=3(x-1)(x+1).
$$

However, a student wrote the following conclusion:

> The derivative is positive between its zeros and negative outside them. Therefore, the function is decreasing on $(-\infty,-1)\cup(1,\infty)$, increasing on $(-1,1)$, has a local minimum at $x=-1$, and a local maximum at $x=1$.

1. Without differentiating again, explain why merely identifying the zeros of the derivative does not justify the stated sign chart, and find the error in the student's reasoning.
2. Construct the correct sign chart for $f'(x)$.
3. Give the correct intervals of monotonicity and the character of the extrema.
4. In each of the three intervals, choose one simple test point and show that the sign of the derivative confirms your classification.

> **Why this problem:** it teaches how to diagnose an error in a completed argument and shows that a correct derivative formula is not enough if its sign is interpreted incorrectly.

## Solution

Zeros of a derivative identify possible sign changes but do not determine the signs by themselves. Here the leading coefficient is positive, and the product of two negative factors is positive. The student's sign chart is reversed.

Without differentiating again, inspect the supplied factors:

| Interval | $x-1$ | $x+1$ | Sign of $f'$ | Behavior |
| --- | --- | --- | --- | --- |
| $(-\infty,-1)$ | $-$ | $-$ | $+$ | Increasing |
| $(-1,1)$ | $-$ | $+$ | $-$ | Decreasing |
| $(1,\infty)$ | $+$ | $+$ | $+$ | Increasing |

Thus there is a local maximum at $(-1,2)$ and a local minimum at $(1,-2)$.

The requested test points confirm the chart:

$$
f'(-2)=3(-3)(-1)=9>0,\quad
f'(0)=3(-1)(1)=-3<0,\quad
f'(2)=3(1)(3)=9>0.
$$

The signs, rather than just the locations of zeros, justify both the monotonicity and the character of the extrema.
