# Problem

## Problem Description
You have shown that the temperature of a substance, \( T \) (in \( \mathrm{K} \) or in \( {}^{\circ}\mathrm{C} \) ), flowing in and out of a container kept at the ambient temperature, \( {T}_{\mathrm{o}} \), with an inflow temperature, \( {T}_{\mathrm{i}} \), and a heat source, \( q \) (in W), can be approximated by the differential equation

\[
{mc}\dot{T} = q + {wc}\left( {{T}_{\mathrm{i}} - T}\right) + \frac{1}{R}\left( {{T}_{\mathrm{o}} - T}\right),
\]

where \( m \) and \( c \) are the substance’s mass and specific heat, and \( R \) is the overall system’s thermal resistance.

When the flow rate, \( w \), is not constant, this model is nonlinear. Let the heat source, \( q \), the flow rate, \( w \), and the ambient and inflow temperatures, \( {T}_{\mathrm{o}} \) and \( {T}_{\mathrm{i}} \), be the inputs and let the temperature, \( T \), be the output, and represent this equation in a block-diagram using only integrators.

Rewrite the differential equation in state-space form.

## Subproblems
1. Identify the system inputs, state variable, and output.
2. Rewrite the differential equation by isolating the highest-order derivative.
3. Express the system in nonlinear state-space form.
4. Define the input vector and corresponding state and output equations.
5. Construct a block-diagram representation using integrators only.
6. Explain why the resulting model is nonlinear when the flow rate varies.

## Additional Information
- The system consists of a well-mixed thermal container.
- Heat transfer occurs through mass flow and thermal resistance to the environment.
- The temperature dynamics are governed by energy balance principles.
- All parameters \( m \), \( c \), and \( R \) are assumed to be constant and positive.

## Constraints
- The block-diagram must use only integrators and algebraic operations.
- The state-space model should explicitly show nonlinear terms.
- Inputs must be clearly defined and physically interpretable.
- No linearization is required in this problem.
