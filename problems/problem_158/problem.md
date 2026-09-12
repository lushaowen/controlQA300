# Problem

## Problem Description
Verify that the state-space equations (5.3) with matrices as in (5.9) are observable except when \( \alpha = 0 \), i.e. there exist some nonzero vector \( x \) and scalar \( \lambda \) that solve Equations (5.10) only when \( \alpha = 0 \).


(5.3):
\[\dot{x} = Ax + Bu,\]
\[y = Cx + Du,\]
(5.9):
\[A = \begin{bmatrix} 0 & 1 \\ 0 & 0 \end{bmatrix}, \quad B = \begin{bmatrix} 1 \\ \beta \end{bmatrix}, \quad C = \begin{bmatrix} \alpha & 1 \end{bmatrix}, \quad D = \gamma. \]
(5.10):
\[Ax = \lambda x, \quad Cx = 0, \quad x \neq 0. \]
## Subproblems
1. Write the eigenvalue equation \( (A - \lambda I)x = 0 \).
2. Determine all eigenvalues \( \lambda \) and corresponding nonzero eigenvectors \( x \).
3. Apply the observability condition \( Cx = 0 \).
4. Identify the parameter values for which the observability condition fails.
5. Interpret the result using the PBH observability test.

## Additional Information
- The observability condition is examined using the Popov–Belevitch–Hautus (PBH) test.
- Matrices \( A \) and \( C \) are taken from equations (5.3) and (5.9).
- The system is linear and time-invariant.
- Scalar parameters may affect structural observability.

## Constraints
- The vector \( x \) must be nonzero.
- Eigenvalue calculations must be exact.
- Matrix dimensions must be respected throughout.
- Conclusions must align with standard observability theory.
