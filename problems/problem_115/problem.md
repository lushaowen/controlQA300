# Problem

## Problem Description
You have shown in that the ordinary differential equation

\[
{RC}{\dot{v}}_{C} + {v}_{C} = v
\]

is an approximate model for the \( {RC} \) electric circuit in Fig. 2.22(a). Calculate the transfer-function from the input voltage, \( v \), to the capacitor voltage, \( {v}_{C} \). Assume that all constants are positive. Is this transfer-function asymptotically stable?
![](images\image.png)
## Subproblems
1. Rewrite the given differential equation in standard first-order linear system form.
2. Apply the Laplace transform under zero initial conditions.
3. Solve for the ratio \( \frac{V_C(s)}{V(s)} \) to obtain the transfer function.
4. Identify the system pole and express it in terms of the circuit parameters.
5. Determine whether the transfer function is asymptotically stable and justify your answer.

## Additional Information
- The circuit consists of a resistor and a capacitor connected in series.
- The capacitor voltage is taken as the system output.
- Zero initial conditions are assumed for Laplace transform analysis.
- Stability is determined by the location of poles in the complex plane.

## Constraints
- All physical parameters \( R \) and \( C \) are strictly positive.
- The system is assumed to be linear and time-invariant.
- Analysis should be carried out using Laplace transform techniques.
- Stability arguments must be mathematically justified.
