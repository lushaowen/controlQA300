# Solution

## Method

The model is not controllable because

\[
\left( \begin{array}{lll} 1 & 0 & 0 \end{array}\right) \left\lbrack  \begin{array}{lll} 0 & 0 & 0 \\  0 & 0 & v \\  0 & 0 & 0 \end{array}\right\rbrack   = 0
\]

so that \( \lambda  = 0 \) is an eigenvalue and

\[
\left( \begin{array}{lll} 1 & 0 & 0 \end{array}\right) \left\lbrack  \begin{matrix} 0 \\  0 \\  v/\ell  \end{matrix}\right\rbrack   = 0.
\]

Physically, from a straight horizontal line the car cannot instantaneously move toward the left or right, which is the motion captured by the linearizaton: only the \( y \) coordinate is affected by the input.

## Teaching Points

1. Linearization can introduce uncontrollable modes.
2. Controllability is a local property dependent on the operating point.
3. Zero eigenvalues often correspond to integrator-like or kinematic states.
4. Physical intuition is essential to interpret mathematical controllability results.
5. Not all physically reachable motions are captured by linearized models.
