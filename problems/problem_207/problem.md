# Problem

## Problem Description
You have shown that the ordinary differential equation

\[
\left( {{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }\right) \dot{\omega } + \left( {{b}_{1} + {b}_{2}}\right) \omega  = \tau  + {gr}\left( {{m}_{1} - {m}_{2}}\right) ,\;{v}_{1} = {r\omega },
\]

is a simplified description of the motion of the elevator in Fig. 2.18(b), where $ \omega $ is the angular velocity of the driving shaft and $ {v}_{1} $ is the elevator’s load linear velocity. Let $ r = 1\mathrm{\;m},{m}_{1} = {m}_{2} = {1000}\mathrm{\;{kg}},{b}_{1} = {b}_{2} = {120}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{J}_{1} = {J}_{2} = {20}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} $, and $ g = \; {10}\mathrm{\;m}/{\mathrm{s}}^{2} $. Use the root-locus method to design a dynamic feedback controller that uses $ \tau $ as control input and the elevator's load vertical position

\[
{x}_{1}\left( t\right)  = {x}_{1}\left( 0\right)  + {\int }_{0}^{t}{v}_{1}\left( \tau \right) {d\tau }
\]

as the measured output so that the closed-loop is capable of asymptotically tracking a constant position reference $ {\bar{x}}_{1}\left( t\right)  = {\bar{x}}_{1}, t \geq  0 $.

## Subproblems
1. Derive the second-order differential equation relating the elevator’s vertical position $ x_1 $ to the control torque $ \tau $.
2. Obtain the open-loop transfer function from $ \tau $ to $ x_1 $, and identify its poles and zeros.
3. Explain why a simple proportional (P) controller may be sufficient for this system despite integrating nature.
4. Construct the root-locus plot for the system under P-control and analyze stability for all $ K > 0 $.
5. Justify whether the closed-loop system can achieve asymptotic tracking of a constant position reference.
6. Discuss the role of symmetry ($ m_1 = m_2 $) in simplifying disturbance rejection.

## Additional Information 
- The elevator system consists of two counterbalanced masses connected by a cable over a pulley driven by a motor.
- Due to the symmetry $ m_1 = m_2 $, the gravitational bias term vanishes, removing a key disturbance source.
- Velocity $ v_1 = r\omega $ implies direct kinematic coupling between rotational and translational motion.
- Position measurement integrates velocity, introducing an additional pole at the origin.
- This makes the plant inherently type-II with respect to position output when combined with inertial dynamics.

## Constraints
- All derivations must assume linear time-invariant (LTI) behavior around nominal operating conditions.
- Do not use state-space methods; only classical frequency-domain (root-locus) techniques are allowed.
- Stability analysis must include root-locus construction and interpretation.
- Final controller should be proper and implementable without derivative action unless necessary.
- Assumptions about initial conditions or disturbances must be explicitly stated.
