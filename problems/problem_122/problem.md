# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
J\dot{\omega} + \left( b + \frac{K_{\mathrm{t}} K_{\mathrm{e}}}{R_{\mathrm{a}}} \right) \omega
= \frac{K_{\mathrm{t}}}{R_{\mathrm{a}}} v_{\mathrm{a}}
\]

is a simplified description of the motion of the rotor of the DC motor in Fig. 2.24, where \( \omega \) is the rotor angular velocity. Calculate the transfer-function from the armature voltage, \( v_{\mathrm{a}} \), to the rotor’s angular velocity, \( \omega \), then calculate the transfer-function from the voltage, \( v_{\mathrm{a}} \), to the motor’s angular position,
\[
\theta = \int_{0}^{t} \omega(\tau)\, d\tau .
\]
Assume that all constants are positive. Are these transfer-functions asymptotically stable?
![](images\image.png)
Fig.2.24
## Subproblems

1. Rewrite the given differential equation in standard first-order LTI form.
2. Apply the Laplace transform under zero initial conditions.
3. Derive the transfer-function from armature voltage to angular velocity.
4. Express the angular position as the integral of angular velocity in the Laplace domain.
5. Determine the transfer-function from armature voltage to angular position.
6. Analyze the asymptotic stability of each transfer-function based on pole locations.

## Additional Information

- The DC motor is modeled as a linear time-invariant system.
- Electrical dynamics of the armature circuit are neglected.
- All parameters \( J, b, K_t, K_e, R_a \) are strictly positive.
- Stability should be assessed using continuous-time system theory.

## Constraints

- Laplace transform techniques must be used.
- Zero initial conditions are assumed.
- Stability conclusions must be justified using pole locations.
- Final expressions should be given in simplified rational form.
