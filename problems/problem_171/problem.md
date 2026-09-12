# Problem

## Problem Description
Let \( {m}_{1} = {m}_{2} = 1\mathrm{\;kg},{b}_{1} = {b}_{2} = {0.1}\mathrm{\;kg}/\mathrm{s},{k}_{1} = 1\mathrm{\;N}/\mathrm{m} \), and \( {k}_{2} = 2\mathrm{\;N}/\mathrm{m} \). Use MATLAB to compute the transfer-function from the force \( {f}_{2} \) to the displacement \( {x}_{2} \).

Is this system asymptotically stable? Use MATLAB to simulate the system assuming zero initial conditions and a constant force \( {f}_{2} = 1\mathrm{\;N} \).

## Subproblems
1. Substitute the given numerical parameters into the state-space model from P5.26.
2. Construct the corresponding state-space matrices \( A \), \( B \), \( C \), and \( D \).
3. Use MATLAB to compute the transfer function from \( f_2 \) to \( x_2 \).
4. Analyze the poles of the transfer function to determine asymptotic stability.
5. Simulate the time response of \( x_2(t) \) for a constant input force.
6. Interpret the steady-state and transient behavior of the system.

## Additional Information
- The system is a two-mass spring-damper mechanical model.
- The input force \( f_2 \) is applied to mass \( m_2 \).
- The output is the displacement of mass \( m_2 \).
- MATLAB Control System Toolbox functions such as `ss`, `zpk`, and `step` may be used.

## Constraints
- Zero initial conditions are assumed.
- The system is continuous-time and linear.
- MATLAB must be used for both transfer-function computation and simulation.
- Stability should be determined based on pole locations.
