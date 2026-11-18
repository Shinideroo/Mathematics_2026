### Exercise 15. Observation Versus Proof
Choose one sequence and one function from this set. For the sequence, compute several values for increasingly large $n$. For the function, prepare a table of values with arguments approaching the limit point from the left and right. Sketch the behavior of both objects.

Compare the observation with the analytical result and explain why a finite number of calculations or a sketch does not constitute a proof that the limit exists.

> **Why this exercise:** teaches how to distinguish intuition and observation from mathematical argument.

## Solution

Choose the sequence from Exercise 1 and the function from Exercise 7.

For the sequence $a_n=(4n^2-3n+1)/(2n^2+5n-7)$, division by $n^2$ proves $a_n\to2$.

| $n$ | $a_n$ (rounded) |
| --- | --- |
| $10$ | $1.526749$ |
| $100$ | $1.937296$ |
| $1000$ | $1.993524$ |
| $10000$ | $1.999350$ |

A schematic plot of these sampled terms is:

~~~text
a_n
2.0  - - - - - - - - - - - - limit 2
                  *      *
          *
1.5   *
      10 100     1000   10000       n
~~~

For $f(x)=(x^2-4x+3)/(x-3)$, cancellation gives $f(x)=x-1$ for $x\ne3$, proving $\lim_{x\to3}f(x)=2$.

| Left $x$ | $f(x)$ | Right $x$ | $f(x)$ |
| --- | --- | --- | --- |
| $2.9$ | $1.9$ | $3.1$ | $2.1$ |
| $2.99$ | $1.99$ | $3.01$ | $2.01$ |
| $2.999$ | $1.999$ | $3.001$ | $2.001$ |

~~~text
 y
 ^           /
2|          o  hole at (3,2)
 |         /
 +---------3----------------> x
~~~

The observations agree with the analytical limits. Finitely many samples or a sketch do not control every sufficiently large index or every point near $3$; the algebraic limit arguments do.
