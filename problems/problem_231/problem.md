# Problem

## Problem Description

You showed in that the temperature of a substance, \( T \) (in \( \mathrm{K} \) or in \( {}^{ \circ  }\mathrm{C} \) ), flowing in and out of a container kept at the ambient temperature, \( {T}_{\mathrm{o}} \) , with an inflow temperature, \( {T}_{\mathrm{i}} \) , and a heat source, \( q \) (in W), can be approximated by the differential equation

\[
{mc}\dot{T} = q + {wc}\left( {{T}_{\mathrm{i}} - T}\right)  + \frac{1}{R}\left( {{T}_{\mathrm{o}} - T}\right) ,
\]

where \( m \) and \( c \) are the substance’s mass and specific heat, and \( R \) is the overall system’s thermal resistance. The input and output flow mass rates are assumed to be equal to \( w \) (in \( \mathrm{{kg}}/\mathrm{s} \) ). Assume that water’s density and specific heat are \( {997.1}\mathrm{\;{kg}}/{\mathrm{m}}^{3} \) and \( c = \) 4186 J/kg K. Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses the heat source \( q \) as the control input and the temperature \( T \) as the measured output for a 50 gal \( \left( { \approx  {0.19}{\mathrm{\;m}}^{3}}\right) \) water heater rated at \( \bar{q} = {40},{000}\mathrm{{BTU}}/\mathrm{h} \; \left( { \approx  {12}\mathrm{\;{kW}}}\right) \) and thermal resistance \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) at ambient temperature, \( {T}_{\mathrm{o}} = {77}^{ \circ  }\mathrm{F} \; \left( { \approx  {25}^{ \circ  }\mathrm{C}}\right) \) . The controller should achieve asymptotic tracking of a reference temperature \( \bar{T} = {140}^{ \circ  }\mathrm{F}\left( { \approx  {60}^{ \circ  }\mathrm{C}}\right) \) without any in/out flow, i.e. \( w = 0 \) . Calculate the corresponding gain and phase margins.

## Subproblems

1. Simplify the thermal model for the no-flow case \( w = 0 \).
2. Derive the transfer function from heat input \( q \) to temperature \( T \).
3. Identify the system order, poles, and steady-state characteristics.
4. Determine the system type and tracking capability for constant references.
5. Justify the need for integral action in the controller.
6. Construct the loop transfer function for the closed-loop system.
7. Use Bode plots to compute gain and phase margins.
8. Apply the Nyquist stability criterion to assess closed-loop stability.
9. Interpret the stability margins in terms of robustness.

## Additional Information

- Heat losses are modeled via a lumped thermal resistance.
- The system is assumed to be well-mixed with uniform temperature.
- Flow disturbances are neglected in this design.
- The heater power rating limits achievable control authority.
- Classical linear control assumptions apply.

## Constraints

- Controller design must use frequency-domain methods.
- The reference temperature must be tracked asymptotically.
- Stability must be verified using both Bode and Nyquist criteria
