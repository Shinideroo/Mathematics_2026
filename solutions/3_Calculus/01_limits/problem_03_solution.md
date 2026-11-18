### Exercise 3. A Square Root and Removing an Indeterminate Form
Compute

$$
\lim_{n\to\infty}\left(\sqrt{n^2+5n}-n\right).
$$

Use the conjugate expression and explain why this transformation removes the difficulty.

> **Why this exercise:** introduces conjugation as a deliberate technique for removing an indeterminate form.

## Solution

Direct subtraction has the indeterminate form $\infty-\infty$. Multiply by the conjugate:

$$
\sqrt{n^2+5n}-n
=\frac{(n^2+5n)-n^2}{\sqrt{n^2+5n}+n}
=\frac{5}{\sqrt{1+5/n}+1}.
$$

The last denominator tends to $2$, so the limit is $5/2$.

The conjugate replaces subtraction of two large nearly equal terms by a quotient with a nonzero limiting denominator. For verification of the approach, subtract $5/2$ from the last expression:

$$
\frac{5}{\sqrt{1+5/n}+1}-\frac52
=-\frac{25}{2n(\sqrt{1+5/n}+1)^2}\longrightarrow0.
$$
