### Problem 2. Maximum Area of a Rectangle
A rectangle has perimeter $40$.

1. Write its area as a function of the length of one side.
2. Determine the domain of this function resulting from the geometry of the problem.
3. Find the dimensions that give the maximum area.
4. Justify that the point found actually gives a maximum.

> **Why this problem:** it teaches the complete optimization scheme: model → domain → derivative → verification and interpretation of the maximum.

## Solution

Let the side lengths be $x$ and $y$. The perimeter constraint is $2x+2y=40$, so $y=20-x$ and

$$
A(x)=x(20-x)=20x-x^2,\qquad 0<x<20.
$$

Strict positivity of both sides gives this geometric domain.

Differentiate: $A'(x)=20-2x$, which vanishes at $x=10$. It is positive before $10$ and negative afterward, so the unique global maximum occurs at $x=y=10$, with area $100$ square units.

Verification by completing the square gives $A(x)=100-(x-10)^2\le100$. The perimeter is $2(10)+2(10)=40$, so the maximizing square satisfies the constraint.
