### Exercise 14. Rotation Matrices
The matrix for a rotation through an angle $\theta$ is

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
$$

Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that

$$
R(\alpha)R(\beta)=R(\alpha+\beta).
$$

Explain the result geometrically.

> **Why this exercise:** shows the consistency between matrix algebra and the geometry of composing rotations.

## Solution

Row-by-column multiplication gives

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta&
-\cos\alpha\sin\beta-\sin\alpha\cos\beta\\
\sin\alpha\cos\beta+\cos\alpha\sin\beta&
-\sin\alpha\sin\beta+\cos\alpha\cos\beta
\end{pmatrix}.
$$

Use the angle-sum identities

$$
\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta,
\qquad
\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta.
$$

Substitution in all four entries gives

$$
R(\alpha)R(\beta)=
\begin{pmatrix}\cos(\alpha+\beta)&-\sin(\alpha+\beta)\\
\sin(\alpha+\beta)&\cos(\alpha+\beta)\end{pmatrix}
=R(\alpha+\beta).
$$

Geometrically, rotations about the origin preserve length and add their angles: first $\beta$, then $\alpha$. As a check, setting $\beta=-\alpha$ gives $R(0)=I$, so the opposite rotation undoes the original rotation.
