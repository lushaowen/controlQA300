# Solution

## Method

We have

\[
\ddot{x} + \alpha \dot{x} + \beta x = \gamma (f + \delta),
\]

where

\[
\alpha = \frac{b}{m}, \quad \beta = \frac{k}{m}, \quad \gamma = \frac{1}{m}, \quad \delta = mg\sin\theta.
\]

This leads to the open-loop transfer function

\[
G(s) = \frac{\gamma}{s^2 + \alpha s + \beta}.
\]

With the given physical parameters, this corresponds to a stable, lightly damped second-order system with natural frequency \( \omega_n = 1 \) and damping ratio \( \zeta = 0.05 \).

The constant input disturbance requires selecting a controller with a pole at the origin. The simplest possible candidate is an integral controller

\[
K(s) = \frac{K}{s}.
\]

The loop transfer function becomes

\[
L(s) = \frac{G(s)}{s} = \frac{\gamma}{s(s^2 + \alpha s + \beta)}.
\]

This system has two stable complex poles and one pole at the origin. The Bode plots and Nyquist diagrams indicate that for gains \( K < 0.1 \), the Nyquist plot produces the correct number of encirclements to guarantee closed-loop stability.

Choosing \( K = 0.05 \), the resulting gain margin is \( 6.02\,\mathrm{dB} \), and the phase margin is approximately \( 89.7^\circ \).

## Teaching Points

1. Modeling constant disturbances as equivalent input forces
2. Relationship between integral control and steady-state error elimination
3. Interpretation of Bode plots for lightly damped systems
4. Application of Nyquist stability criterion to systems with integrators
5. Trade-offs between robustness and controller gain selection
