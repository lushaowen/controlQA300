# Problem

## Problem Description

Assume that water’s density and specific heat are \( \rho  = {997.1}\mathrm{\;{kg}}/{\mathrm{m}}^{3} \) and \( c = 4186 \) J/kg K. Design a feedback controller

\[
q = K\left( {\bar{T} - T}\right)
\]

for a 50 gal \( \left( { \approx  {0.19}{\mathrm{\;m}}^{3}}\right) \) water heater rated at \( \bar{q} = {40},{000}\mathrm{{BTU}}/\mathrm{h}\left( { \approx  {12}\mathrm{\;{kW}}}\right) \) and thermal resistance \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) at ambient temperature, \( {T}_{\mathrm{o}} = {77}^{ \circ  }\mathrm{F}\left( { \approx  {25}^{ \circ  }\mathrm{C}}\right) \) .

Select \( K \) such that the closed-loop system calculated with the linearized model from P5.37 is asymptotically stable and so that a heater initially at ambient temperature never exceeds its maximum power with a flow

\[
w\left( t\right)  = \frac{\bar{w}}{2}\left( {1 + \cos \left( {\omega t}\right) }\right)
\]

and \( \bar{T} = {140}^{ \circ  }\mathrm{F}\left( { \approx  {60}^{ \circ  }\mathrm{C}}\right) \) .

Calculate the resulting closed-loop time-constant in hours and compare your answer with the open-loop time-constant. Is the closed-loop system capable of asymptotically tracking a constant reference temperature \( \bar{T}\left( t\right)  = \bar{T}, t \geq  0 \) ?

Use MATLAB to plot the temperature of the water during 3 days. Compute the average water temperature over the entire period and over the last 2 days. 

## Subproblems

1. Determine an appropriate operating point for linearization of the nonlinear water heater model.
2. Derive the linearized transfer function between heater power input and water temperature.
3. Analyze the closed-loop stability conditions for proportional feedback control.
4. Select a controller gain \( K \) that ensures stability and respects actuator saturation constraints.
5. Compute and compare open-loop and closed-loop time constants.
6. Analyze steady-state tracking performance for a constant reference temperature.
7. Simulate the nonlinear closed-loop system under time-varying water flow conditions.
8. Compute average water temperature metrics and compare with a previous approximation-based result.

## Additional Information

- The heater dynamics are governed by an energy balance equation.
- Linearization is performed around a steady-state operating point.
- The control law is purely proportional.
- The nonlinear model is used for simulation validation.
- Flow disturbances are periodic and bounded.
- MATLAB/Simulink is used for numerical simulation.

## Constraints

- Heater power must not exceed its rated maximum at any time.
- Linearized analysis must be consistent with P5.37.
- Simulations must be based on the nonlinear model.
- All assumptions must be clearly stated.
- Units must be handled consistently throughout the analysis.
