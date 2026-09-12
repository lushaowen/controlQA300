# Problem

## Problem Description
Maximize \( y\left( t\right) \) to show that \( {t}_{\mathrm{p}} \) and \( {y}_{\mathrm{p}} \) given in (6.8) are the time and value of the first peak of the step response of an underdamped second-order system with transfer-function \( G\left( s\right) \) as in P6.2 with \( 0 < \zeta  < 1.\; \) Hint: Differentiate \( y\left( t\right) \) and solve \( \dot{y}\left( t\right)  = 0 \) .

## Subproblems
1. Derive the expression for the derivative of the step response \( \dot{y}(t) \) of an underdamped second-order system.
2. Solve the equation \( \dot{y}(t) = 0 \) to find the time instants \( t_d \) where extrema (peaks/valleys) occur.
3. Identify which solution (which value of \( k \)) corresponds to the *first* peak \( t_p \).
4. Substitute \( t = t_p \) back into the expression for \( y(t) \) to derive the peak value \( y_p \).
5. Simplify the final expression for \( y_p \) to match the standard form given in many textbooks.

## Additional Information
- The problem refers to a standard underdamped second-order system with transfer function of the form \( G(s) = \frac{\omega_n^2}{s^2 + 2\zeta\omega_n s + \omega_n^2} \), where \( 0 < \zeta < 1 \) is the damping ratio and \( \omega_n > 0 \) is the natural frequency.
- The damped natural frequency is \( \omega_d = \omega_n \sqrt{1 - \zeta^2} \).
- The step response is given by \( y(t) = 1 - \frac{e^{-\zeta \omega_n t}}{\sqrt{1-\zeta^2}} \sin(\omega_d t + \phi_d) \), where \( \phi_d = \cos^{-1}(\zeta) \) or \( \phi_d = \arctan\left(\frac{\sqrt{1-\zeta^2}}{\zeta}\right) \).
- Equation (6.8), which is not provided but is standard, likely states:
    \( t_p = \frac{\pi}{\omega_d} \)
    \( y_p = 1 + e^{-\zeta \pi / \sqrt{1-\zeta^2}} \)

## Constraints
- The solution must proceed via differentiation of \( y(t) \) and solving \( \dot{y}(t) = 0 \), as per the hint.
- Trigonometric identities and algebraic simplifications must be shown clearly.
- The final results for \( t_p \) and \( y_p \) must be expressed in terms of \( \zeta \) and \( \omega_n \) (or \( \omega_d \)).

---

