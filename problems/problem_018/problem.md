# Problem: Closed-Loop Speed Control of a Rotating Machine Using Proportional Feedback

## Problem Description
Consider the rotating machine model developed in Problems P2.10 and P2.12. The system consists of two inertias \( J_1 \) and \( J_2 \) coupled by a belt, with viscous friction acting on each inertia.

A proportional feedback controller is introduced to regulate the angular velocity of inertia \( J_2 \). The control law is given by
\[
\tau(t) = K\left( \overline{\omega}_2 - \omega_2(t) \right),
\]
where \( \overline{\omega}_2 \) is the desired angular velocity.

Using the system parameters from P2.13, analyze the resulting closed-loop system.

---

## Subproblems
1. Derive the closed-loop differential equation governing the system.
2. Solve the closed-loop equation for \( \omega_2(t) \).
3. Select the controller gain \( K \) such that the closed-loop time constant is 3 s.
4. Compare the closed-loop time constant with the open-loop time constant.
5. Calculate the steady-state tracking error.
6. Sketch or simulate the response for different initial conditions.

---

## Additional Information
- The belt is inextensible and does not slip.
- The controller is purely proportional (no integral action).
- The desired speed is
  \[
  \overline{\omega}_2 = 4~\mathrm{rad/s}.
  \]
- System parameters are identical to those used in P2.13.

---

## Constraints
- The closed-loop system must be derived analytically.
- Clearly distinguish between time constant and torque.
- Do not introduce additional control dynamics.
- Initial conditions must be properly transformed.
