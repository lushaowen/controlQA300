# Problem

## Problem Description

with a constant in/out flow of \( {20}\mathrm{{gal}}/\mathrm{h}\left( { \approx  {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s}}\right) \) at ambient temperature. Is the closed-loop system capable of asymptotically rejecting this constant in/out flow perturbation?

## Subproblems

1. Explain the effect of a constant in/out flow disturbance on the thermal dynamics of the system.
2. Determine whether the closed-loop system satisfies the conditions for asymptotic disturbance rejection.
3. Identify the role of the proportional and integral gains in rejecting constant disturbances.
4. Analyze how the choice of controller parameters influences stability and transient behavior.
5. Discuss the physical realizability constraints imposed on the control input.

## Additional Information

- The system under consideration is the same as in Problem P4.40, except for the inclusion of a constant flow disturbance.
- The disturbance represents a continuous inflow and outflow of fluid at ambient temperature.
- The controller structure includes proportional and integral terms.
- Reference temperature tracking is evaluated over multiple days to assess long-term performance.
- Heater power is constrained to be non-negative and bounded.

## Constraints

- Controller parameters must ensure closed-loop stability.
- Control action must remain within physically realizable limits (no negative power).
- Oscillatory responses are undesirable due to actuator limitations.
- The disturbance is constant and does not vary with time.
- Qualitative explanations must accompany quantitative results.
