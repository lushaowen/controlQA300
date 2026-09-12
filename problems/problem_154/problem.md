# Problem

## Problem Description

with a sinusoidal in/out flow perturbation

\[
w\left( t\right)  = \frac{\bar{w}}{2}\left( {1 + \cos \left( {\omega t}\right) }\right) ,
\]

where \( \bar{w} = {20}\mathrm{{gal}}/\mathrm{h}\left( { \approx  {21} \times  {10}^{-6}{\mathrm{\;m}}^{3}/\mathrm{s}}\right) \) at ambient temperature and \( \omega  = {2\pi }/{24}{\mathrm{\;h}}^{-1} \) . What can this in/out flow represent? Use the approximation \( w\left( t\right) \left( {{T}_{\mathrm{i}} - T\left( t\right) }\right)  \approx  \bar{w}\left( {{T}_{\mathrm{i}} - }\right. \; \bar{T} \) ). When is this approximation reasonable? Can you solve the problem without approximating? Is the closed-loop system capable of asymptotically rejecting this in/out flow perturbation? If not, what form would the controller need to have in order to reject this disturbance?

## Subproblems

1. Interpret the physical meaning of the sinusoidal in/out flow perturbation.
2. Explain the assumptions behind the approximation involving the average temperature.
3. Determine under what conditions the approximation is valid.
4. Analyze the closed-loop system’s ability to reject sinusoidal disturbances.
5. Identify the controller structure required for asymptotic rejection of the disturbance.
6. Discuss whether the disturbance rejection conclusion depends on the approximation.

## Additional Information

- The system dynamics are based on the thermal model developed in Problem P4.38.
- The disturbance is periodic with a 24-hour cycle.
- Ambient and inlet temperatures are assumed constant unless stated otherwise.
- The controller considered is a static gain controller.
- Sinusoidal disturbances are common in environmental and energy systems.

## Constraints

- Linear system assumptions apply.
- Controller parameters must remain physically realizable.
- Asymptotic rejection is defined in the steady-state sense.
- The disturbance frequency is fixed and known.
- Qualitative explanations must accompany mathematical reasoning.
