# Problem

## Problem Description
For \( w = 0 \), we have

\[
G(s) = \frac{\beta}{s + \alpha},
\]

\[
\alpha = \frac{1}{Rmc},
\]

\[
\beta = \frac{1}{mc}.
\]

You have shown  that the temperature of a substance, \( T \) (in \( \mathrm{K} \) or in \( {}^{ \circ  }\mathrm{C} \) ), flowing in and out of a container kept at the ambient temperature, \( {T}_{\mathrm{o}} \) , with an inflow temperature, \( {T}_{\mathrm{i}} \) , and a heat source, \( q \) (in W), can be approximated by the differential equation 

\[
{mc}\dot{T} = q + {wc}\left( {{T}_{\mathrm{i}} - T}\right)  + \frac{1}{R}\left( {{T}_{\mathrm{o}} - T}\right) ,
\]

where \( m \) and \( c \) are the substance’s mass and specific heat, and \( R \) is the overall system's thermal resistance. The input and output flow mass rates are assumed to be equal to \( w \) in \( \mathrm{{kg}}/\mathrm{s} \). Assume that water’s density and specific heat are \( {997.1}\mathrm{\;{kg}}/{\mathrm{m}}^{3} \) and \( c = {4186}\mathrm{\;J}/\mathrm{{kg}} \) K.

Use the root-locus method to design a dynamic feedback controller that uses the heat source \( q \) as the control input and the temperature \( T \) as the measured output for a 50 gal \( \left( { \approx  {0.19}{\mathrm{\;m}}^{3}}\right) \) water heater rated at \( \bar{q} = {40},{000}\mathrm{{BTU}}/\mathrm{h}\left( { \approx  {12}\mathrm{\;{kW}}}\right) \) and thermal resistance \( R = {0.27}\mathrm{\;K}/\mathrm{W} \) at ambient temperature, \( {T}_{\mathrm{o}} = {77}^{ \circ  }\mathrm{F}\left( { \approx  {25}^{ \circ  }\mathrm{C}}\right) \).

The controller should achieve asymptotic tracking of a reference temperature

\[
\bar{T} = {140}^{ \circ  }\mathrm{F} \; \left( { \approx  {60}^{ \circ  }\mathrm{C}}\right)
\]

without any in/out flow, i.e. \( w = 0 \).

## Subproblems
1. Simplify the thermal model under the assumption \( w = 0 \).
2. Derive the transfer function from heat input \( q \) to temperature \( T \).
3. Identify the open-loop pole and system type.
4. Explain why integral action is required for constant temperature tracking.
5. Propose a suitable dynamic controller structure.
6. Construct the loop transfer function of the compensated system.
7. Analyze the root-locus and determine stability conditions.
8. Discuss the physical meaning o
