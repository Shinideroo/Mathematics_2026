### Problem 10. A Cable Through Water and Land
Point $A$ lies on one bank of a river of width $100$ m, and point $B$ lies on the other bank, $500$ m along the bank from the point directly opposite $A$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

> **Why this problem:** it checks whether the student can independently translate a spatial description and two different costs into a single function to be optimized.

## Solution

Let $O$ be the point on the opposite bank directly across from $A$. Measure $x$ meters from $O$ toward $B$ along that bank, with the cable leaving the water at $C$. Then $OB=500$, $OC=x$, the underwater length is $\sqrt{100^2+x^2}$, and the remaining land length is $500-x$ when $0\le x\le500$.

Let $c>0$ denote the unspecified land cost per meter; the underwater cost is $2c$. The model is

$$
K(x)=c\left(2\sqrt{10000+x^2}+500-x\right),
\qquad 0\le x\le500.
$$

For completeness, allowing any exit point on the straight opposite bank would replace $500-x$ by $|500-x|$. Points with $x<0$ are worse than $x=0$, and for $x>500$ the cost increases. Thus the restricted domain loses no optimum in this bank model.

Differentiate:

$$
K'(x)=c\left(\frac{2x}{\sqrt{10000+x^2}}-1\right).
$$

At a critical point, $2x=\sqrt{10000+x^2}$, so $3x^2=10000$ and

$$
x_*=\frac{100}{\sqrt3}\approx57.735\ \mathrm m.
$$

Also

$$
K''(x)=\frac{20000c}{(10000+x^2)^{3/2}}>0,
$$

so it is the unique global minimizer. The underwater and land lengths are respectively $200/\sqrt3$ and $500-100/\sqrt3$ meters. The minimum cost is $c(500+100\sqrt3)$.

As a check, this is less than both endpoint costs $700c$ and $200\sqrt{26}\,c$. No absolute monetary cost can be given because $c$ is not specified.
