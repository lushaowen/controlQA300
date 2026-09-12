# Problem

## Problem Description
Show that the connection of the state-space systems

\[
{\dot{x}}_{g} = {A}_{g}{x}_{g} + {B}_{g}{u}_{g}
\]

\[
{y}_{g} = {C}_{g}{x}_{g} + {D}_{g}{u}_{g}
\]


and

\[
{\dot{x}}_{k} = {A}_{k}{x}_{k} + {B}_{k}{u}_{k}
\]

\[
{y}_{k} = {C}_{k}{x}_{k} + {D}_{k}{u}_{k}
\]

in feedback,

\[
{u}_{g} = {y}_{k},\;{u}_{k} = \bar{y} - y,\;y = {y}_{g},
\]

can be represented in state-space form (5.3) by the matrices

\[
A = \left\lbrack  \begin{matrix} {A}_{g} - {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}{C}_{g} & {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k} \\   - {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g} & {A}_{k} - {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1}{D}_{g}{C}_{k} \end{matrix}\right\rbrack ,
\]

\[
B = \left\lbrack  \begin{matrix} {B}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k} \\  {B}_{k}{\left( I + {D}_{g}{D}_{k}\right) }^{-1} \end{matrix}\right\rbrack ,
\]

\[
C = \left\lbrack  \begin{array}{ll} {\left( I + {D}_{g}{D}_{k}\right) }^{-1}{C}_{g} & {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{C}_{k} \end{array}\right\rbrack ,
\]

\[
D = {D}_{g}{\left( I + {D}_{k}{D}_{g}\right) }^{-1}{D}_{k}
\]

Draw a block-diagram representing the connection.  
Hint: The letter \( I \) represents a square identity matrix, which for SISO systems is equal to the number 1; the formulas, as given, work also for MIMO systems.

## Subproblems
1. Write the closed-loop interconnection equations by eliminating internal signals.
2. Express the combined system in augmented state-space form.
3. Derive the composite system matrices \( A \), \( B \), \( C \), and \( D \).
4. Verify the invertibility conditions required for \( \left( I + D_g D_k \right)^{-1} \).
5. Interpret the resulting structure for both SISO and MIMO cases.

## Additional Information
- Both subsystems are assumed to be linear and time-invariant.
- Matrix dimensions are compatible for feedback interconnection.
- The derivation applies to both single-input single-output and multi-input multi-output systems.
- Algebraic loops are resolved using matrix inversion.

## Constraints
- All matrix inverses must be well-defined.
- State vectors \( x_g \) and \( x_k \) must be kept distinct.
- Intermediate algebraic steps should preserve matrix dimensions.
- Final expressions must match the standard state-space form.
