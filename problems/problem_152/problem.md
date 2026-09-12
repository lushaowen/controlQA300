# Problem

## Problem Description
You have shown in that the temperature of a substance, \( T \) (in \( \mathrm{K} \) or in \( {}^{ \circ  }\mathrm{C} \) ), flowing in and out of a container kept at the ambient temperature, \( {T}_{\mathrm{o}} \) , with an inflow temperature, \( {T}_{\mathrm{i}} \) , and a heat source, \( q \) (in W), can be approximated by the differential equation

\[
{mc}\dot{T} = q + {wc}\left( {{T}_{\mathrm{i}} - T}\right)  + \frac{1}{R}\left( {{T}_{\mathrm{o}} - T}\right) ,
\]

where \( m \) and \( c \) are the substance’s mass and specific heat, and \( R \) is the overall system’s thermal resistance. The input and output flow mass rates are assumed to be equal to \( w \) (in \( \mathrm{{kg}}/\mathrm{s} \) ). Assume that water’s density and specific heat are \( \rho  = {997.1}\mathrm{\;{kg}}/{\mathrm{m}}^{3} \) and \( c = {4186}\mathrm{\;J}/\mathrm{{kg}}\mathrm{K} \) . Design a feedback controller

\[
q = K\left( {\bar{T} - T}\right)
\]

for a 50 gal \( \left( { \approx  {0.19}{\mathrm{\;m}}^{3}}\right) \) water heater rated at \( \bar{q} = {40},{000}\mathrm{{BTU}}/\mathrm{h}\left( { \approx  {12}\mathrm{\;{kW}}}\right) \) and thermal resistance \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) at ambient temperature \( {T}_{\mathrm{o}} = {77}^{ \circ  }\mathrm{F}\left( { \approx  {25}^{ \circ  }\mathrm{C}}\right) \) . Select \( K \) such that the closed-loop system is asymptotically stable and so that a heater initially at ambient temperature never exceeds its maximum power without any in/out flow, \( w = 0 \) , and \( \bar{T} = {140}^{ \circ  }\mathrm{F}\left( { \approx  {60}^{ \circ  }\mathrm{C}}\right) \) . Calculate the resulting closed-loop time-constant in hours and compare your answer with the open-loop time-constant. Is the closed-loop system capable of asymptotically tracking a constant reference temperature \( \bar{T}\left( t\right)  = \bar{T}, t \geq  0 \) ? Use MATLAB to plot the temperature of the water during 3 days. Compute the average water temperature over the entire period and over the last 2 days. Compare your answer with .

 with a controller

\[
q\left( t\right)  = {K}_{\mathrm{p}}e\left( t\right)  + {K}_{\mathrm{i}}{\int }_{0}^{t}e\left( \tau \right) {d\tau },
\]

where \( e = \bar{T} - T \) .

## Subproblems
1. Write the transfer function of the PI controller in the Laplace domain.
2. Derive the closed-loop characteristic equation.
3. Determine the conditions on \( K_p \) and \( K_i \) for internal stability.
4. Explain why integral action enables reference tracking and disturbance rejection.
5. Select controller gains that lead to non-oscillatory closed-loop behavior.
6. Compute the resulting closed-loop time constant.
7. Verify that the maximum heater power constraint is not violated.
8. Interpret the simulation results over a multi-day horizon.

## Additional Information
- The plant dynamics are first-order thermal dynamics.
- The disturbance corresponds to a constant inflow/outflow of water.
- The controller includes one integrator and one proportional term.
- MATLAB simulations are used to evaluate time-domain performance.
- Negative heater power is physically unrealizable.

## Constraints
- The heater power must remain within physical limits.
- Only PI control is allowed.
- Closed-loop poles should lie in the open left-half plane.
- Excessive oscillations are not acceptable.
- Controller gains must be physically realizable.
