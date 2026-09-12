# Solution

## Method
If only radial trust is used then

\[
\dot{\widetilde{x}} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack  \widetilde{x} + \left\lbrack  \begin{matrix} 0 \\  \frac{1}{m} \\  0 \end{matrix}\right\rbrack  {u}_{r}.
\]

Note that

\[
\left( \begin{array}{lll} {2\Omega } & 0 & {1\Omega } \end{array}\right) \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack   = 0
\]

so that \( \lambda  = 0 \) is an eigenvalue of \( A \) . Moreover

\[
\left( \begin{array}{lll} {2\Omega } & 0 & {1\Omega } \end{array}\right) \left\lbrack  \begin{matrix} 0 \\  \frac{1}{m} \\  0 \end{matrix}\right\rbrack   = 0
\]

which means that the system is not controllable using \( {u}_{r} \) alone.

## Teaching Points
1. Application of controllability concepts to linearized orbital dynamics
2. Interpretation of uncontrollable modes through eigenstructure analysis
3. Limitations of single-axis actuation in multi-state systems
4. Connection between mathematical controllability and physical maneuverability
5. Importance of actuator placement in spacecraft control design
