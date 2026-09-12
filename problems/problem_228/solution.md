# Solution

## Method

We recall from P6.25 the following state-space description of the system,

\[
A = \begin{bmatrix}
0 & 1 & 0 & 0 \\
-\dfrac{k_s(m_s + m_u)}{m_s m_u} & -\dfrac{b_s(m_s + m_u)}{m_s m_u} & \dfrac{k_u}{m_u} & \dfrac{b_u}{m_u} \\
0 & 0 & 0 & 1 \\
\dfrac{k_s}{m_u} & \dfrac{b_s}{m_u} & -\dfrac{k_u}{m_u} & -\dfrac{b_u}{m_u}
\end{bmatrix},
\quad
B = \begin{bmatrix}
0 \\ 0 \\ 0 \\ -1
\end{bmatrix}.
\]

The corresponding output matrices are

\[
C = \begin{bmatrix}
-\dfrac{k_s}{m_s} & -\dfrac{b_s}{m_s} & 0 & 0
\end{bmatrix},
\quad
D = -1.
\]

Substituting the numerical values from P6.25 yields the transfer function

\[
G(s) =
\frac{
-s^{4} - 595.5 s^{3} - 1.737 \times 10^{4} s^{2}
-1.147 \times 10^{-10} s - 4.461 \times 10^{-9}
}{
s^{4} + 595.5 s^{3} + 1.737 \times 10^{4} s^{2}
+1.861 \times 10^{5} s + 3.867 \times 10^{6}
}.
\]

The Bode plots and Nyquist diagrams are shown in Figures G.17 and G.18. The dominant pole pair is located at

\[
s = -1.2605 \pm 15.677j.
\]

From the Bode magnitude plot, the peak magnitude occurs at approximately

\[
\omega = 15.6\,\mathrm{rad/s}.
\]

This value is consistent with the theoretical resonant frequency given by

\[
\omega = \omega_n \sqrt{1 - 2\zeta^2},
\]

which also yields \( \omega = 15.6\,\mathrm{rad/s} \). The Bode plots therefore confirm that the designed suspension achieves the desired natural frequency and damping ratio.

## Teaching Points

1. Frequency-response interpretation of high-order mechanical systems
2. Identification of dominant pole pairs in multi-degree-of-freedom models
3. Relationship between resonant frequency and damping ratio
4. Interpretation of Bode magnitude peaks in vehicle suspension dynamics
5. Validation of time-domain design objectives using frequency-domain tools
6. Physical meaning of sprung-mass acceleration amplification
