### Problem 15. Recovering a Function from Its Derivative and a Condition
The function $F$ satisfies

$$
F'(x)=2xe^{x^2}
$$

and

$$
F(0)=3.
$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

> **Why this problem:** it combines recognition of substitution, the meaning of the constant of integration, and an initial condition in one problem, using only mechanisms introduced earlier.

## Solution

Recognize the chain-rule pattern: the derivative of $x^2$ is the factor $2x$. Set $u=x^2$ to integrate:

$$
F(x)=\int2xe^{x^2}\,dx=\int e^u\,du=e^{x^2}+C.
$$

This is the entire family on $\mathbb R$. Use the condition:

$$
F(0)=e^0+C=1+C=3,
$$

so $C=2$ and the required function is

$$
F(x)=e^{x^2}+2.
$$

Verification: $F'(x)=e^{x^2}(2x)=2xe^{x^2}$ and $F(0)=1+2=3$. Thus both the derivative and the initial condition hold.
