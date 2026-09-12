# Problem

## Problem Description
 with a constant in/out flow of \( {20}\mathrm{{gal}}/\mathrm{h}\left( { \approx  {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s}}\right) \) at ambient temperature. Is the closed-loop system capable of asymptotically rejecting this constant in/out flow perturbation?

## Subproblems
1. Incorporate the constant in/out flow into the thermal model.
2. Determine how the flow rate modifies the system parameter \( \alpha \).
3. Compute the new open-loop time constant.
4. Compute the closed-loop time constant using the same controller gain as in P4.38.
5. Analyze the effect of the flow disturbance on the steady-state temperature.
6. Determine whether the closed-loop system can asymptotically reject a constant flow disturbance.
7. Interpret the simulation results over a multi-day period.

## Additional Information
- The inflow temperature equals the ambient temperature.
- The flow rate is constant over time.
- Controller structure and gain are unchanged from P4.38.
- Average temperatures are computed over the entire simulation horizon.
- MATLAB is used for time-domain simulation.

## Constraints
- Only proportional feedback is allowed.
- Heater power must remain below its rated maximum.
- The flow disturbance is constant and uncontrollable.
- Stability must be assessed via closed-loop pole locations.
- Comparisons should be made with the zero-flow case.
