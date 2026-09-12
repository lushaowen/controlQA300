# Problem

## Problem Description
 the water level, \( h \), in a rectangular water tank of cross-sectional area \( A \) can be modeled as the integrator

\[
\dot{h} = \frac{1}{A} w_{\text{in}}
\]

where \( w_{\text{in}} \) is the inflow rate. If water is allowed to flow out from the bottom of the tank through an orifice then

\[
\dot{h} = \frac{1}{A}\left( w_{\text{in}} - w_{\text{out}} \right).
\]

The outflow rate can be approximated by

\[
w_{\text{out}} = \frac{1}{R} \left( p_{\mathrm{t}} - p_{\mathrm{a}} \right)^{1/\alpha},
\]

where the resistance \( R > 0 \) and \( \alpha > 0 \) depend on the shape of the outflow orifice, \( p_{\mathrm{a}} \) is the ambient pressure outside the tank, and

\[
p_{\mathrm{t}} = p_{\mathrm{a}} + \rho g h
\]

is the pressure at the water level, where \( \rho \) is the water density and \( g \) is the gravitational acceleration.

Combine these equations to write a nonlinear differential equation in state-space relating the water inflow rate, \( w_{\text{in}} \), to the water tank level, \( h \), and represent this equation in a block-diagram using only integrators.

## Subproblems
1. Express the outflow rate \( w_{\text{out}} \) as a function of the water level \( h \).
2. Substitute the pressure expression into the outflow equation.
3. Combine the inflow and outflow expressions into a single differential equation.
4. Identify the state, input, and output variables.
5. Write the resulting nonlinear system in state-space form.
6. Construct a block-diagram representation using only integrators and static nonlinearities.

## Additional Information
- The tank has a constant cross-sectional area.
- The system exhibits nonlinear behavior due to the outflow term.
- All parameters \( A, R, \alpha, \rho, g \) are positive constants.
- The ambient pressure cancels out in the final expression.

## Constraints
- The state variable must be the water level \( h \).
- The input must be the inflow rate \( w_{\text{in}} \).
- The output must be the water level \( h \).
- Only integrators may represent dynamic elements.
