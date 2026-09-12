# Solution

## Method

Calculation is tedious and left to the reader.

For the given data, around \( \theta = 0 \):

\[
A_0 =
\begin{bmatrix}
0 & 1 & 0 \\
-16.8000 & -0.0171 & 0.0143 \\
1.4000 & 0.0014 & -0.0095
\end{bmatrix},
\quad
B_0 =
\begin{bmatrix}
0 \\
-0.1429 \\
0.0952
\end{bmatrix}
\]

\[
C =
\begin{bmatrix}
1 & 0 & 0 \\
0 & 1 & 0
\end{bmatrix},
\quad
D =
\begin{bmatrix}
0 \\
0
\end{bmatrix}
\]

From which the transfer functions from \( u \) to \( \theta \) and \( \dot{x}_{\mathrm{c}} \) are:

\[
\frac{\Theta(s)}{U(s)} =
\frac{-0.14286\,s}{(s + 0.008333)(s^{2} + 0.01833s + 16.8)}
\]

\[
\frac{\dot{X}_{\mathrm{c}}(s)}{U(s)} =
\frac{0.095238(s^{2} + 0.015s + 14.7)}{(s + 0.008333)(s^{2} + 0.01833s + 16.8)}
\]

All poles lie in the left half-plane; therefore, the equilibrium at \( \theta = 0 \) is asymptotically stable.

---

Around \( \theta = \pi \):

\[
A_{\pi} =
\begin{bmatrix}
0 & 1 & 0 \\
16.8000 & -0.0171 & -0.0143 \\
1.4000 & -0.0014 & -0.0095
\end{bmatrix},
\quad
B_{\pi} =
\begin{bmatrix}
0 \\
0.1429 \\
0.0952
\end{bmatrix}
\]

The transfer functions are:

\[
\frac{\Theta(s)}{U(s)} =
\frac{0.14286\,s}{(s + 0.008333)(s - 4.09)(s + 4.108)}
\]

\[
\frac{\dot{X}_{\mathrm{c}}(s)}{U(s)} =
\frac{0.095238(s + 3.842)(s - 3.827)}{(s + 0.008333)(s - 4.09)(s + 4.108)}
\]

Since there exists a pole at \( s = 4.09 \) in the right half-plane, the equilibrium at \( \theta = \pi \) is unstable.

## Teaching Points

1. Linearization of nonlinear mechanical systems around equilibrium points
2. Physical interpretation of state-space matrices
3. Relationship between pole locations and asymptotic stability
4. Fundamental difference between downward and upright pendulum equilibria
5. Use of transfer functions to analyze control-relevant system behavior
