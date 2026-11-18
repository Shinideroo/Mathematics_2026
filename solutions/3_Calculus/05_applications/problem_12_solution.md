### Problem 12. Complete Model and Computer Verification
A museum wants to create a rectangular exhibition room next to an existing straight wall. The side along the wall does not need to be built. The remaining three sides are to be constructed to two different standards: the two sides perpendicular to the wall cost $300\ \mathrm{PLN/m}$ each, while the side parallel to the wall costs $500\ \mathrm{PLN/m}$. The budget is $30\,000\ \mathrm{PLN}$.

Build a model that maximizes the area of the room and prepare a complete analysis containing:

- definition of variables and units,
- mathematical model,
- domain resulting from the problem statement,
- computation of the derivative,
- determination and verification of the optimum,
- interpretation of the result,
- graph of the objective function,
- numerical verification of several values near the optimum found.

Finally, indicate which part of the solution required modeling the problem and which part was only the execution of the calculation. Produce the graph and computer calculations only after completing the mathematical solution, and treat them as verification.

> **Why this problem:** it checks full transfer to a new problem with unequal side costs and integrates the process from model construction to independent verification.

## Solution

Let $x$ meters be the length of each side perpendicular to the existing wall, and let $y$ meters be the length parallel to it. The area is $A=xy$ square meters. Two sides cost $300$ PLN/m each and the third costs $500$ PLN/m, giving the budget constraint

$$
600x+500y\le30000,\qquad x>0,\quad y>0.
$$

At the maximum the full budget is used: otherwise, for fixed positive $x$, increasing $y$ slightly would increase area while remaining affordable. Thus

$$
y=60-\frac65x,\qquad
A(x)=60x-\frac65x^2,\qquad 0<x<50.
$$

The domain ensures both dimensions are positive. The derivative is

$$
A'(x)=60-\frac{12}{5}x.
$$

It vanishes at $x=25$, and $A''(x)=-12/5<0$. More strongly,

$$
A(x)=750-\frac65(x-25)^2\le750.
$$

Hence the unique global optimum is

$$
x=25\ \mathrm m,\qquad y=30\ \mathrm m,\qquad
A_{\max}=750\ \mathrm m^2.
$$

Verification of the budget gives $2(300)(25)+500(30)=15000+15000=30000$ PLN. The dimensions are feasible, and the completed-square identity proves global optimality without numerical evidence.

**Graph and computer verification, after the mathematical solution.** The objective is a downward parabola with vertex $(25,750)$ and limiting zeros at $0$ and $50$. The endpoints are excluded because they describe degenerate rooms.

~~~mermaid
xychart-beta
    x-axis "x (m)" [0, 5, 10, 15, 20, 25, 30, 35, 40, 45, 50]
    y-axis "Area (square meters)" 0 --> 800
    line [0, 270, 480, 630, 720, 750, 720, 630, 480, 270, 0]
~~~

The plotted samples trace the parabola; use the displayed formula for its exact smooth curve. The numerical verification is reproducible with JavaScript:

~~~javascript
for (const x of [20, 24, 24.9, 25, 25.1, 26, 30]) {
  const y = (30000 - 600 * x) / 500;
  console.log(x.toFixed(1), y.toFixed(2), (x * y).toFixed(3));
}
~~~

| $x$ (m) | $y$ (m) | $A$ (square meters) |
| --- | --- | --- |
| $20.0$ | $36.00$ | $720.000$ |
| $24.0$ | $31.20$ | $748.800$ |
| $24.9$ | $30.12$ | $749.988$ |
| $25.0$ | $30.00$ | $750.000$ |
| $25.1$ | $29.88$ | $749.988$ |
| $26.0$ | $28.80$ | $748.800$ |
| $30.0$ | $24.00$ | $720.000$ |

The computations confirm the analytical optimum but do not establish it by themselves. Defining the dimensions, identifying the unequal side costs, and translating the budget into a constraint were the modeling steps. Differentiating the resulting quadratic and evaluating its maximum were the calculation steps.
