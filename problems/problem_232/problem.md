# Problem

## Problem Description

with a sinusoidal in/out flow perturbation:

\[
w\left( t\right)  = \frac{\bar{w}}{2}\left( {1 + \cos \left( {\omega t}\right) }\right) ,
\]

where \( \bar{w} = {20}\mathrm{{gal}}/\mathrm{h}\left( { \approx  {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s}}\right) \) at ambient temperature and \( \omega  = {2\pi }/{24}{\mathrm{\;h}}^{-1} \) . Approximate \( w\left( t\right) \left( {{T}_{\mathrm{i}} - T\left( t\right) }\right)  \approx  w\left( t\right) \left( {{T}_{\mathrm{i}} - \bar{T}}\right) \) .

## Subproblems

1. Modify the thermal model to include a nonzero, time-varying flow rate.
2. Apply the given approximation to linearize the flow-temperature interaction term.
3. Derive the resulting transfer function from heat input to temperature.
4. Identify the disturbance frequencies introduced by the sinusoidal flow.
5. Determine the controller structure required to track constant and sinusoidal references.
6. Construct the loop transfer function of the closed-loop system.
7. Analyze the pole-zero structure of the loop transfer function.
8. Use Nyquist plots to assess closed-loop stability.
9. Discuss the role of controller zeros in shaping system response.

## Additional Information

- The flow perturbation is slow compared to the thermal dynamics.
- The approximation assumes small temperature deviations around the operating point.
- Ambient and inflow temperatures are constant.
- The system is linearized about a steady-state operating condition.
- Classical frequency-domain control techniques are applicable.

## Constraints

- Controller design must accommodate both constant and sinusoidal inputs.
- Stability must be verified using the Nyquist criterion.
- Controller poles must include those required by the internal model principle.
- All poles must lie in the left-half plane for stability.
- Physical interpretability of controller structure should be maintained.
