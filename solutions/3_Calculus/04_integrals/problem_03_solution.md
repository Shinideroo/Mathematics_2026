### Problem 3. Recognizing Basic Antiderivatives
Compute

$$
\int\left(2e^x+3\cos x-4\sin x\right)\,dx.
$$

Match each term with a known derivative and verify the entire result with one differentiation.

> **Why this problem:** it builds a catalogue of basic antiderivatives from known derivatives.

## Solution

We use $(e^x)'=e^x$, $(\sin x)'=\cos x$, and $(\cos x)'=-\sin x$. Therefore termwise integration gives

$$
\int(2e^x+3\cos x-4\sin x)\,dx
=2e^x+3\sin x+4\cos x+C.
$$

The sign in the last term is positive because differentiating $4\cos x$ produces $-4\sin x$. Differentiating the whole result checks it at once:

$$
(2e^x+3\sin x+4\cos x+C)'=2e^x+3\cos x-4\sin x.
$$
