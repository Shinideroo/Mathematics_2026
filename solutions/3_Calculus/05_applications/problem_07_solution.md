### Problem 7. Exponential Growth
Assume the model

$$
N(t)=N_0e^{kt},\qquad k>0.
$$

1. Verify by differentiation that the model satisfies the relation $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $N_0$.

> **Why this problem:** it shows the connection between the exponential function and a growth rate proportional to the current value, without introducing a separate technique for solving differential equations.

## Solution

Differentiate the model using the chain rule:

$$
N'(t)=N_0ke^{kt}=kN(t).
$$

For a nonzero initial population, doubling means $N(T)=2N_0$. Cancelling $N_0$ gives $e^{kT}=2$, hence

$$
T=\frac{\ln2}{k}.
$$

More generally, $N(t+T)/N(t)=e^{kT}=2$, so the same duration doubles the population starting at any time. The factor $N_0$ cancels because growth is proportional to the current population, making the doubling time independent of initial size.

The population interpretation uses $N_0>0$. If $N_0=0$, the model is identically zero and there is no meaningful unique doubling time. No numerical $N_0$ or $k$ is specified, so the result remains symbolic.
