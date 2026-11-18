### Exercise 12. Exponential Function Limit
Compute

$$
\lim_{x\to0}(1+3x)^{1/x}.
$$

Connect the result with the limit from Exercise 5 and show the appropriate transformation.

> **Why this exercise:** teaches how to recognize the classical pattern after a transformation.

## Solution

Near zero, $1+3x>0$, so the real power is well defined. Put $u=3x$. Then

$$
(1+3x)^{1/x}=\left((1+u)^{1/u}\right)^3.
$$

The classical real-variable limit $(1+u)^{1/u}\to e$ as $u\to0$ therefore gives

$$
\lim_{x\to0}(1+3x)^{1/x}=e^3.
$$

It is the same pattern as Exercise 5, where $u=1/n$ approaches zero through a sequence. For a check covering both sides, the logarithm of the original expression is $3\ln(1+u)/u\to3$, using the standard limit $\ln(1+u)/u\to1$. Exponentiating again yields $e^3$.
