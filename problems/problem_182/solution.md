# Solution

## Method
---
**P5.43.**  
If the orbital period is \( T = 11 \, \text{h} \), the corresponding angular velocity is:

\[
\Omega = \frac{2\pi}{T} = \frac{2\pi}{11 \times 3600} \approx 1.59 \times 10^{-4} \, \text{rad/s}.
\]

Thus,

\[
R = \left( \frac{GM}{\Omega^2} \right)^{1/3} \approx 2.52 \times 10^7 \, \text{m}.
\]

Stability can be evaluated by calculating the matrix \( A \) from P5.42:

\[
A =
\begin{bmatrix}
0 & 1.0000 & 0 \\
0.0000 & 0 & 0.0003 \\
0 & -0.0003 & 0
\end{bmatrix}
\]

and its eigenvalues:

\[
1.0e-03 \times
\begin{bmatrix}
-0.0000 + 0.0000i \\
0.0000 + 0.1587i \\
0.0000 - 0.1587i
\end{bmatrix}
\]

These reveal two imaginary eigenvalues. Consequently, the equilibrium is not asymptotically stable. It is not unstable either, since no eigenvalue has a positive real part.

Since \( A \) depends only on the angular velocity \( \Omega \), it does not depend on the mass of the satellite. It only depends on the mass of the Earth.

---
## Teaching Points

1. Relationship between orbital period and angular velocity
2. Application of gravitational equilibrium to satellite orbits
3. Interpretation of eigenvalues in orbital stability analysis
4. Distinction between asymptotic stability and marginal stability
5. Independence of orbital stability from satellite mass
6. Role of central body mass in orbital dynamics
7. Practical relevance to GPS satellite design
