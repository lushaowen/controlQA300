# Solution

## Method
System is in state-space with

\[
f\left( {x,\gamma }\right)  = \left( \begin{matrix}  - a{x}_{1} + {b\gamma } \\   - \left( {c + {x}_{1}}\right) {x}_{2} + d \end{matrix}\right) ,
\]

Linearization leads to

\[
{\left. A = \frac{\partial f}{\partial x}\right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = {\left. \left\lbrack  \begin{matrix}  - a & 0 \\   - {x}_{2} &  - \left( {c + {x}_{1}}\right)  \end{matrix}\right\rbrack  \right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = \left\lbrack  \begin{matrix}  - a & 0 \\   - {\bar{x}}_{2} &  - \left( {c + {\bar{x}}_{1}}\right)  \end{matrix}\right\rbrack
\]

\[
B = {\left. \frac{\partial f}{\partial \gamma }\right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = {\left. \left\lbrack  \begin{array}{l} b \\  0 \end{array}\right\rbrack  \right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = \left\lbrack  \begin{array}{l} b \\  0 \end{array}\right\rbrack
\]

\[
C = {\left. \frac{\partial g}{\partial x}\right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = {\left. \left\lbrack  \begin{array}{ll} 0 & 1 \end{array}\right\rbrack  \right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = \left\lbrack  \begin{array}{ll} 0 & 1 \end{array}\right\rbrack
\]

\[
D = {\left. \frac{\partial g}{\partial \gamma }\right| }_{x = \bar{x},\gamma  = \overline{\gamma }} = 0.
\]

Calculating the transfer-function:

\[
C{\left( sI - A\right) }^{-1}B + D = \left\lbrack  \begin{array}{ll} 0 & 1 \end{array}\right\rbrack  {\left\lbrack  \begin{matrix} s + a & 0 \\  {\bar{x}}_{2} & s + c + {\bar{x}}_{1} \end{matrix}\right\rbrack  }^{-1}\left\lbrack  \begin{array}{l} b \\  0 \end{array}\right\rbrack
\]

\[
= \frac{1}{\left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }\left\lbrack  \begin{array}{ll} 0 & 1 \end{array}\right\rbrack  \left\lbrack  \begin{matrix} s + c + {\bar{x}}_{1} & 0 \\   - {\bar{x}}_{2} & s + a \end{matrix}\right\rbrack  \left\lbrack  \begin{array}{l} b \\  0 \end{array}\right\rbrack
\]

\[
= \frac{-b{\bar{x}}_{2}}{\left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }.
\]

The negative sign on the numerator means that when insulin concentration goes up, glucose goes down.

## Teaching Points
1. Linearization of physiological nonlinear models
2. Jacobian-based derivation of state-space matrices
3. State-space to transfer-function conversion
4. Interpretation of system gain sign in feedback systems
5. Relationship between mathematical models and biological behavior
