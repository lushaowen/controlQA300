# Problem

## Problem Description
You have shownthat the ordinary differential equation

\[
J\dot{\omega } + \left( {b + \frac{{K}_{\mathrm{e}}{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}}\right) \omega  = \frac{{K}_{\mathrm{t}}}{{R}_{\mathrm{a}}}{v}_{\mathrm{a}}
\]

is a simplified description of the motion of the rotor of the DC motor in Fig. 2.24. Let the voltage \( {v}_{\mathrm{a}} \) be the control input and the rotor angular velocity \( \omega \) be the measured output. Let

\[
J = {227} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2},\;
{K}_{\mathrm{t}} = {0.02}\mathrm{\;N}\mathrm{\;m}/\mathrm{A},\;
{K}_{\mathrm{e}} = {0.02}\mathrm{\;V}\mathrm{\;s}/\mathrm{{rad}},
\]

\[
b = {289.4} \times  {10}^{-6}\mathrm{\;{kg}} \; {\mathrm{m}}^{2}/\mathrm{s},\;
{R}_{\mathrm{a}} = {7\Omega }.
\]

Use the root-locus method to design a dynamic feedback controller so that the closed-loop system is capable of asymptotically tracking a constant reference input

\[
\overline{\omega }\left( t\right)  = \overline{\omega }, \quad t \geq  0 .
\]
![](images\image.png)
Fig. 2.24
## Subproblems
1. Derive the transfer function from the armature voltage \( v_a \) to the rotor angular velocity \( \omega \).
2. Identify the open-loop pole and gain of the DC motor model.
3. Explain why asymptotic tracking of a constant reference requires a pole at the origin.
4. Propose a suitable dynamic controller structure to achieve zero steady-state error.
5. Form the loop transfer function for the compensated system.
6. Sketch and interpret the root-locus of the compensated system.
7. Select an appropriate controller gain that ensures internal stability and satisfactory transient response.

## Additional Information
- The DC motor model neglects armature inductance.
- Back electromotive force (EMF) is proportional to rotor speed.
- Constant reference tracking implies zero steady-state error.
- Root-locus analysis is performed in the continuous-time domain.
- Stability is determined by the location of closed-loop poles.

## Constraints
- Controller design must rely on classical root-locus techniques.
- Stability conclusions must be justified by pole locations.
- Parameter values must be used as given.
- Physical interpretation should accompany control design decisions.
