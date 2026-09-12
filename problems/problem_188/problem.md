# Problem

## Problem Description
After insulin has been released in the plasma at a rate \( u \) , its concentration, \( \gamma \) , does not reach steady-state values instantaneously. Instead,

\[
\dot{\gamma } =  - {f\gamma } + {gu}
\]

Combine the results from P5.49-P5.51 to show that the transfer function from \( \widetilde{u} \) to \( \widetilde{y} \) is

\[
\frac{\widetilde{Y}\left( s\right) }{\widetilde{U}\left( s\right) } = \frac{-{gb}{\bar{x}}_{2}}{\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }.
\]

Use the value \( g = 1/5{\mathrm{\;{min}}}^{-1} \) and \( f = 1/5 \) from [Ste+03] and substitute numerical values from P5.51 to calculate the corresponding poles and zeros.

## Subproblems
1. Write the dynamic equation describing insulin concentration in plasma.
2. Derive the transfer function from insulin release rate \( u \) to insulin concentration \( \gamma \).
3. Combine this result with the linearized glucose–insulin model.
4. Derive the overall transfer function from \( \widetilde{u} \) to \( \widetilde{y} \).
5. Substitute the numerical parameter values provided.
6. Identify all poles and zeros of the resulting transfer function.
7. Interpret the dynamical implications of the pole locations.

## Additional Information
- The insulin–glucose model is based on results from P5.49–P5.51.
- Parameters \( f \) and \( g \) describe insulin absorption and clearance.
- All models are linearized about an equilibrium point.
- Reference [Ste+03] provides experimentally validated parameter values.
- The system is continuous-time and linear time-invariant.

## Constraints
- Use linear systems and transfer-function theory.
- Numerical substitution must follow the given parameter values.
- Stability conclusions must be based on pole locations.
- Ignore nonlinearities and disturbances.
