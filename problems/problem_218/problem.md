# Problem

## Problem Description
You have shown  that

\[
\dot{x} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack  x
+\left\lbrack  \begin{matrix} 0 \\  0 \\  1/m \end{matrix}\right\rbrack  {u}_{\mathrm{t}},
\quad
x = \left( \begin{matrix} r - R \\  \dot{r} \\  R\left( {\omega  - \Omega }\right)  \end{matrix}\right),
\]

\[
y = \left\lbrack  \begin{array}{lll} 1 & 0 & 0 \end{array}\right\rbrack  x,
\quad
y = r - R
\]

is a simplified description of the motion of a satellite orbiting earth as in Fig. 5.18, where \( r \) is the satellite’s radial distance from the center of the earth, \( \omega \) is the satellite’s angular velocity, \( m \) is the mass of the satellite, \( M \) is the mass of the earth, \( G \) is the universal gravitational constant, and \( {u}_{\mathrm{t}} \) is a force applied by a thruster in the tangential direction.

These equations were obtained by linearizing around the equilibrium orbit

\[
{u}_{\mathrm{t}}\left( t\right)  = {u}_{\mathrm{r}}\left( t\right)  = \dot{r}\left( t\right)  = 0,
\quad
r\left( t\right)  = R,
\quad
\omega \left( t\right)  = \Omega,
\]

where \( {\Omega }^{2}{R}^{3} = {GM} \).

Let \( M \approx  6 \times  {10}^{24}\mathrm{\;kg} \) and
\( G \approx  {6.7} \times  {10}^{-11}\mathrm{\;N\,m^{2}/kg^{2}} \).

Use MATLAB to calculate the transfer-function from the tangential thrust \( {u}_{\mathrm{t}} \) to the radial distance deviation \( y \) for a \( {1600}\mathrm{\;kg} \) GPS satellite in medium earth orbit (MEO) with a period of \( {11}\mathrm{\;h} \).

Use the root-locus method to design a dynamic feedback controller that uses \( {u}_{\mathrm{t}} \) as the control input and \( y \) as the measured output, and that can regulate the radial distance of the satellite in closed-loop.

## Subproblems
1. Compute the orbital angular velocity \( \Omega \) from the given orbital period.
2. Determine the nominal orbit radius using the gravitational equilibrium condition.
3. Substitute numerical values to obtain the state-space matrices.
4. Use MATLAB to compute the transfer function from \( u_t \) to \( y \).
5. Identify the pole–zero structure of the open-loop plant.
6. Explain why the open-loop system is marginally stable.
7. Propose a dynamic compensator suitable for root-locus design.
8. Analyze how added poles and zeros affect stability and performance.

## Additional Information
- The model corresponds to the Clohessy–Wiltshire (Hill’s) equations.
- Only tangential thrust is used for control.
- Radial thrust is assumed to be zero.
- The control objective is orbital radius regulation, not tracking.
- Linear analysis is valid for small deviations from the nominal orbit.

## Constraints
- Controller design must use classical root-locus techniques.
- Only the radial distance \( y \) is available for feedback.
- The controller must stabilize all closed-loop modes.
- Added poles and zeros must lie in the open left half-plane.
