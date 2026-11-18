### Problem 8. Number of Requests Handled by a Server
The rate at which requests arrive at a server during the first 5 minutes is described by the function

$$
r(t)=100+20t\quad [\mathrm{requests/min}],\qquad 0\le t\le5.
$$

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $r(0)$ and $r(5)$.

> **Why this problem:** it shows the integral as summation of a varying rate in an example directly related to computer science.

## Solution

Integrating a rate in requests per minute over minutes gives a total number of requests:

$$
R=\int_0^5(100+20t)\,dt
=[100t+10t^2]_0^5=500+250=750.
$$

The average arrival rate is

$$
r_{\mathrm{avg}}=\frac{750}{5}=150\ \mathrm{requests/min}.
$$

The endpoint rates are $r(0)=100$ and $r(5)=200$ requests/min. Their arithmetic mean is $(100+200)/2=150$, equal to the integral average because the rate is linear.

The same computation gives the trapezoid area $5(100+200)/2=750$, independently verifying the total.
