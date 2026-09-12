# Problem

## Problem Description

You have shown that the ordinary differential equation

\[
\left( {{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} +{m}_{2}}\right) }\right) \dot{\omega }
+\left( {{b}_{1} + {b}_{2}}\right) \omega
= \tau + {gr}\left( {{m}_{1} - {m}_{2}}\right),
\;{v}_{1} = {r\omega },
\]

is a simplified description of the motion of the elevator in Fig. 2.18(b), where \( \omega \) is the angular velocity of the driving shaft and \( {v}_{1} \) is the elevator’s load linear velocity.
Let

\[
r = 1\mathrm{\;m},\;
{m}_{1} = {m}_{2} = 1000\mathrm{\;kg},\;
{b}_{1} = {b}_{2} = 120\mathrm{\;kg\,m}^{2}/\mathrm{s},\;
{J}_{1} = {J}_{2} = 20\mathrm{\;kg\,m}^{2},
\; g = 10\mathrm{\;m/s}^{2}.
\]

Use Bode plots and the Nyquist stability criterion to design a dynamic feedback controller that uses \( \tau \) as control input and the elevator’s load vertical position

\[
{x}_{1}\left( t\right)
={x}_{1}\left( 0\right)
+\int_{0}^{t}{v}_{1}\left( \tau \right) d\tau
\]

as measured output so that the closed loop is capable of asymptotically tracking a constant position reference
\( {\bar{x}}_{1}\left( t\right) = {\bar{x}}_{1},\; t \ge 0 \).
Calculate the corresponding gain and phase margins.

## Subproblems

1. Simplify the elevator dynamics under the assumption \( m_1 = m_2 \).
2. Derive the transfer function from torque input \( \tau \) to velocity output \( v_1 \).
3. Derive the transfer function from torque input \( \tau \) to position output \( x_1 \).
4. Identify the pole structure of the open-loop plant.
5. Determine whether the plant contains an integrator and interpret its effect on tracking.
6. Use Bode plots to assess open-loop frequency response characteristics.
7. Apply the Nyquist stability criterion to assess closed-loop stability.
8. Determine whether additional controller dynamics are required for asymptotic tracking.
9. Calculate the gain margin and phase margin for a suitable controller gain.

## Additional Information

- The elevator system is assumed to be linear and time-invariant.
- Gravitational effects cancel due to equal masses.
- Zero initial conditions are assumed for Laplace-domain analysis.
- Stability refers to asymptotic stability of the closed-loop system.
- Only frequency-domain tools (Bode and Nyquist) are to be used.

## Constraints

- The controller must be physically realizable.
- Tracking must be achieved without steady-state error.
- Stability must be justified using the Nyquist criterion.
- Gain and phase margins must be explicitly stated.
- Standard control-theoretic assumptions and notation must be used.
