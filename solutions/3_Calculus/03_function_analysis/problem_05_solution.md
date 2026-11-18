### Problem 5. An Exponential Function with a Maximum
Analyze the monotonicity and extrema of

$$
f(x)=xe^{-x}.
$$

Also examine the behavior as $x\to\infty$ and explain how the limit affects the shape of the graph on the right-hand side.

> **Why this problem:** it combines the derivative with a limit in the description of the global behavior of a function.

## Solution

The domain is $\mathbb R$, and the product rule gives

$$
f'(x)=e^{-x}(1-x).
$$

Since $e^{-x}>0$, $f$ increases for $x<1$ and decreases for $x>1$. Therefore its unique global maximum is $f(1)=1/e$, at $x=1$.

As $x\to+\infty$,

$$
xe^{-x}=\frac{x}{e^x}\longrightarrow0^+,
$$

because exponential growth dominates linear growth. For example, $e^x\ge x^2/2$ for $x>0$, giving $0\le xe^{-x}\le2/x$.

The graph crosses at $(0,0)$, rises to $(1,1/e)$, then falls toward the right-hand horizontal asymptote $y=0$ from above. On the left it tends to $-\infty$, consistent with a global maximum and no global minimum. The second derivative $e^{-x}(x-2)$ is negative at $1$, independently confirming a strict local maximum.
