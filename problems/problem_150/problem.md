# Problem

## Problem Description
You have shown in P2.49 that the temperature of a substance, \( T \) (in \( \mathrm{K} \) or in \( {}^{ \circ  }\mathrm{C} \) ), flowing in and out of a container kept at the ambient temperature, \( {T}_{\mathrm{o}} \) , with an inflow temperature, \( {T}_{\mathrm{i}} \) , and a heat source, \( q \) (in W), can be approximated by the differential equation

\[
{mc}\dot{T} = q + {wc}\left( {{T}_{\mathrm{i}} - T}\right)  + \frac{1}{R}\left( {{T}_{\mathrm{o}} - T}\right) ,
\]

where \( m \) and \( c \) are the substance’s mass and specific heat, and \( R \) is the overall system’s thermal resistance. The input and output flow mass rates are assumed to be equal to \( w \) (in \( \mathrm{{kg}}/\mathrm{s} \) ). Assume that water’s density and specific heat are \( \rho  = {997.1}\mathrm{\;{kg}}/{\mathrm{m}}^{3} \) and \( c = {4186}\mathrm{\;J}/\mathrm{{kg}}\mathrm{K} \) . Design a feedback controller

\[
q = K\left( {\bar{T} - T}\right)
\]

for a 50 gal \( \left( { \approx  {0.19}{\mathrm{\;m}}^{3}}\right) \) water heater rated at \( \bar{q} = {40},{000}\mathrm{{BTU}}/\mathrm{h}\left( { \approx  {12}\mathrm{\;{kW}}}\right) \) and thermal resistance \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) at ambient temperature \( {T}_{\mathrm{o}} = {77}^{ \circ  }\mathrm{F}\left( { \approx  {25}^{ \circ  }\mathrm{C}}\right) \) . Select \( K \) such that the closed-loop system is asymptotically stable and so that a heater initially at ambient temperature never exceeds its maximum power without any in/out flow, \( w = 0 \) , and \( \bar{T} = {140}^{ \circ  }\mathrm{F}\left( { \approx  {60}^{ \circ  }\mathrm{C}}\right) \) . Calculate the resulting closed-loop time-constant in hours and compare your answer with the open-loop time-constant. Is the closed-loop system capable of asymptotically tracking a constant reference temperature \( \bar{T}\left( t\right)  = \bar{T}, t \geq  0 \) ? Use MATLAB to plot the temperature of the water during 3 days. Compute the average water temperature over the entire period and over the last 2 days. Compare your answer with .

## Subproblems
1. Rewrite the thermal model in standard first-order state-space form.
2. Derive the open-loop transfer function from heater power to temperature.
3. Determine the closed-loop transfer function under proportional feedback.
4. Find the stability condition on the gain \( K \).
5. Determine the maximum allowable gain that respects the heater power constraint.
6. Compute and compare the open-loop and closed-loop time constants.
7. Analyze whether the closed-loop system can asymptotically track a constant reference temperature.
8. Interpret the simulation results in terms of average temperature and tracking error.

## Additional Information
- Heat losses to the environment are modeled as linear conduction.
- The heater is assumed to respond instantaneously to control commands.
- All parameters are constant over time.
- MATLAB simulations assume continuous-time dynamics.
- Temperature averages are computed using time-domain integration.

## Constraints
- Only proportional feedback is allowed.
- The heater power must not exceed its rated maximum.
- Initial temperature equals ambient temperature.
- No inflow or outflow is present during controller design.
- Stability analysis must be based on pole locations.
