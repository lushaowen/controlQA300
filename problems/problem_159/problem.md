# Problem

## Problem Description

Compute the linearized equations for the pendulum in a cart model, Equations (5.20), developed in Section 5.6. Let  

\( {m}_{\mathrm{p}} = 2\mathrm{\;kg},\quad {m}_{\mathrm{c}} = 10\mathrm{\;kg},\quad \ell = 1\mathrm{\;m}, \)  

\( {b}_{\mathrm{p}} = 0.01\mathrm{\;kg\,m^{2}/s},\quad {b}_{\mathrm{c}} = 0.1\mathrm{\;kg/s},\quad r = \ell/2, \)  

and  

\[
{J}_{\mathrm{p}} = \frac{m\ell^{2}}{12}.
\]

Use MATLAB to compute the transfer functions from the control input \( u \) to the pendulum angle \( \theta \) and from \( u \) to the cart velocity \( \dot{x}_{\mathrm{c}} \) around the equilibrium points calculated with  

\[
\overline{\theta} = 0,\quad \overline{\theta} = \pi,\quad \bar{u} = 0.
\]

Determine whether each equilibrium point is asymptotically stable.
(5.20):
\[(J_p + m_p r^2) \ddot{\theta} + m_p r \ddot{x}_c \cos \theta + b_p \dot{\theta} + m_p g r \sin \theta = 0,\]
\[m_p r \ddot{\theta} \cos \theta + (m_p + m_c) \ddot{x}_c + b_c \ddot{x}_c - m_p r \dot{\theta}^2 \sin \theta = u,
\]
## Subproblems

1. Write the linearized state-space equations of the cart–pendulum system around \( \overline{\theta} = 0 \).
2. Compute the state-space matrices \( A_0, B_0, C, D \) for the downward equilibrium.
3. Derive the transfer functions from input \( u \) to outputs \( \theta \) and \( \dot{x}_{\mathrm{c}} \).
4. Analyze the pole locations and determine the stability of the system around \( \overline{\theta} = 0 \).
5. Repeat steps 1–4 for the upright equilibrium point \( \overline{\theta} = \pi \).
6. Compare the stability properties of the two equilibrium configurations.

## Additional Information

- The system is assumed to operate near the specified equilibrium points.
- Linearization is performed using first-order Taylor expansion.
- MATLAB’s `ss` and `tf` commands may be used to compute transfer functions.
- Gravity and friction effects are included through the given parameters.

## Constraints

- Use linearized dynamics only; nonlinear terms should be neglected.
- Stability must be assessed using pole locations of the transfer functions.
- Numerical results should be consistent with the given physical parameters.
- Clearly distinguish between the two equilibrium configurations.
