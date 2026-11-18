### Problem 14. Continuity and Differentiability of a Piecewise Function
Investigate the behavior at $x=0$ of

$$
f(x)=
\begin{cases}
x^2,&x\ge0, \\
ax,&x<0.
\end{cases}
$$

For which values of $a$ is the function continuous? For which values do the one-sided derivatives exist and agree? For which value of $a$ is the function differentiable? Explain why continuity alone is not sufficient.

> **Why this problem:** it requires an organized argument and a clear distinction between two concepts.

## Solution

Here $f(0)=0$. For every real $a$,

$$
\lim_{x\to0^-}ax=0,\qquad
\lim_{x\to0^+}x^2=0=f(0).
$$

Thus the function is continuous at zero for **all** $a$.

Use the one-sided difference quotients at zero:

$$
f'_-(0)=\lim_{h\to0^-}\frac{ah}{h}=a,
\qquad
f'_+(0)=\lim_{h\to0^+}\frac{h^2}{h}=0.
$$

Both one-sided derivatives exist for every real $a$, but they agree exactly when $a=0$. Hence $f$ is differentiable at zero exactly for $a=0$, with derivative $0$.

For $a\ne0$, the graph joins continuously but has different left and right slopes. This verifies why continuity alone does not guarantee differentiability.
