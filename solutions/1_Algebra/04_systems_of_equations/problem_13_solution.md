### Exercise 13. Does Every Equation Add New Information?
Consider the system

$$
x_1+x_2=10,\qquad x_2+x_3=8,\qquad x_1-x_3=2.
$$

Solve it and check whether all three equations are independently necessary to describe the solution set. If one follows from the others, show this by calculation.

> **Why this exercise:** teaches how to recognize redundant equations within a system.

## Solution

The third equation is redundant: subtracting the second from the first gives

$$
(x_1+x_2)-(x_2+x_3)=10-8
\quad\Longrightarrow\quad x_1-x_3=2.
$$

Let $x_2=s$. The first two equations give

$$
(x_1,x_2,x_3)=(10-s,s,8-s),\qquad s\in\mathbb R.
$$

Check the third: $(10-s)-(8-s)=2$. Thus the family satisfies all equations and there are infinitely many solutions. Only two of the three equations are needed; the third supplies no new restriction.
