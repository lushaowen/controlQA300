# Problem

## Problem Description
You showed in P5.42 that

\[
\dot{x} = \left\lbrack  \begin{matrix} 0 & 1 & 0 \\  3{\Omega }^{2} & 0 & {2\Omega } \\  0 &  - {2\Omega } & 0 \end{matrix}\right\rbrack  x + \left\lbrack  \begin{matrix} 0 \\  0 \\  1/m \end{matrix}\right\rbrack  {u}_{\mathrm{t}},\;x = \left( \begin{matrix} r - R \\  \dot{r} \\  R\left( {\omega  - \Omega }\right)  \end{matrix}\right) ,
\]

\[
y = \left\lbrack  \begin{array}{lll} 1 & 0 & 0 \end{array}\right\rbrack  x,\;y = r - R
\]

is a simplified description of the motion of a satellite orbiting earth as in Fig. 5.18, where \( r \) is the satellite’s radial distance from the center of the earth, \( \omega \) is the satellite’s angular velocity, \( m \) is the mass of the satellite, \( M \) is the mass of the earth, \( G \) is the universal gravitational constant, and \( {u}_{\mathrm{t}} \) is a force applied by a thruster in the tangential direction.

These equations were obtained by linearizing around the equilibrium orbit \( {u}_{\mathrm{t}}\left( t\right)  = {u}_{\mathrm{r}}\left( t\right)  = \dot{r}\left( t\right)  = 0, r\left( t\right)  = R \) , and \( \omega \left( t\right)  = \Omega \) , where \( {\Omega }^{2}{R}^{3} = {GM} \) .

Let \( M \approx  6 \times  {10}^{24}\mathrm{\;{kg}} \) be the mass of the earth, and let \( G \approx  {6.7} \times  {10}^{-{11}}\mathrm{\;N}{\mathrm{\;m}}^{2}/{\mathrm{{kg}}}^{2} \) .

Use MATLAB to calculate the transfer-function from the tangential thrust, \( {u}_{\mathrm{t}} \) , to the radial distance deviation, \( y \) , for a \( {1600}\mathrm{\;{kg}} \) GPS satellite in medium earth orbit (MEO) with a period of 11 h.

Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses tangential thrust \( {u}_{\mathrm{t}} \) as the control input and the radial distance \( y \) as the measured output and that can regulate the radial distance of the satellite, \( y \) , in closed-loop. Calculate the corresponding gain and phase margins.
![](images\image.png)
Fig.5.18
## Subproblems
1. Determine the orbital radius \( R \) and angular velocity \( \Omega \) from the given orbital period.
2. Construct the state-space model and compute the transfer function from \( u_t \) to \( y \).
3. Identify the open-loop poles and discuss the inherent stability of the system.
4. Analyze the limitations of using proportional control alone.
5. Propose a dynamic compensator to modify the open-loop frequency response.
6. Use Nyquist plots to verify closed-loop stability.
7. Determine the admissible range of controller gain.
8. Compute and interpret the gain and phase margins.

## Additional Information
- The system model is obtained by linearization about a circular orbit.
- Only tangential thrust is available as a control input.
- MATLAB functions such as `ss`, `ss2tf`, `bode`, `nyquist`, and `margin` are app
