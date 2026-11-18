### Exercise 4. Powers and Oscillation
Analyze

$$
\left(\frac23\right)^n,\qquad \left(\frac32\right)^n,\qquad (-1)^n,\qquad \frac{(-1)^n}{n}.
$$

For each sequence, describe the type of behavior and justify your answer.

> **Why this exercise:** organizes the basic types of sequence behavior and shows that oscillation does not always rule out convergence.

## Solution

1. $(2/3)^n\to0$, since a positive geometric sequence with ratio less than $1$ decays to zero.
2. $(3/2)^n\to+\infty$. For example, Bernoulli's inequality gives $(1+1/2)^n\ge1+n/2$, an unbounded lower bound.
3. $(-1)^n$ has no limit: even-index terms equal $1$ and odd-index terms equal $-1$. Subsequences of a convergent sequence would have to share the same limit.
4. $(-1)^n/n\to0$, because

$$
-\frac1n\le\frac{(-1)^n}{n}\le\frac1n,
$$

and the squeeze theorem applies.

Thus persistent oscillation prevents convergence in case 3, whereas oscillation with shrinking amplitude still permits convergence in case 4. The absolute values $1$ and $1/n$ verify that distinction.
