### Problem 13. A Multi-Layer Composition
For

$$
f(x)=e^{\sin(x^2)}
$$

compute the derivative. First write the layers

$$
x\longrightarrow x^2\longrightarrow \sin(x^2)\longrightarrow e^{\sin(x^2)}
$$

and explain why differentiation moves through them in the reverse order.

> **Why this problem:** it develops the chain rule as a method for working with multiple layers.

## Solution

The layers are

$$
x\longrightarrow x^2\longrightarrow\sin(x^2)
\longrightarrow e^{\sin(x^2)}.
$$

Differentiate the outermost exponential, then its sine input, then the square input:

$$
f'(x)=e^{\sin(x^2)}\cos(x^2)\cdot2x.
$$

Thus $f'(x)=2xe^{\sin(x^2)}\cos(x^2)$. The chain rule proceeds from the final output back through its inputs, multiplying their local rates of change.

For verification, $\ln f(x)=\sin(x^2)$ implies $f'(x)/f(x)=2x\cos(x^2)$, yielding the same expression.
