# Problem

## Problem Description

You have  that the ordinary differential equation

\[
J\dot{\omega } + \left( {b + \frac{{K}_{\mathrm{e}}{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}}\right) \omega  = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}{v}_{\mathrm{a}}
\]

is a simplified description of the motion of the rotor of the DC motor in Fig. 2.24. Let the voltage, \( {v}_{\mathrm{a}} \) , be the control input and the rotor angular velocity, \( \omega \) , be the measured output. Let \( J = {227} \times  {10}^{-6}{\mathrm{{kgm}}}^{2},{K}_{\mathrm{t}} = {0.02}\mathrm{\;N}\mathrm{\;m}/\mathrm{A},{K}_{\mathrm{e}} = {0.02}\mathrm{\;V}\mathrm{\;s}/\mathrm{{rad}}, b = {289.4} \times \; {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s} \) , and \( {R}_{\mathrm{a}} = {7\Omega } \) . Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller so that the closed-loop system is capable of asymptotically tracking a constant reference input \( \overline{\omega }\left( t\right)  = \overline{\omega }, t \geq  0 \) . Calculate the corresponding gain and phase margins.

## Subproblems

1. Derive the transfer function from armature voltage to rotor angular velocity.
2. Identify the system type and determine steady-state tracking capabilities.
3. Explain why asymptotic tracking of a constant reference requires an integrator.
4. Propose a suitable dynamic feedback controller structure.
5. Form the loop transfer function of the controlled system.
6. Use Bode plots to assess stability margins.
7. Apply the Nyquist stability criterion to verify closed-loop stability.
8. Interpret the gain and phase margins in terms of robustness.

## Additional Information

- The DC motor model neglects armature inductance.
- All parameters are assumed constant and accurately known.
- The system is linear and time-invariant.
- Frequency-domain methods are applicable for controller design.
- Ideal sensing of angular velocity is assumed.

## Constraints

- Controller design must be performed using frequency-domain techniques.
- Stability must be justified using both Bode and Nyquist methods.
- Asymptotic tracking of a constant reference is required.
- Gain and phase margins must be explicitly calculated.
- Classical control assumptions apply.
