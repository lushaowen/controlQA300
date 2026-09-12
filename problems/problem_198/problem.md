# Problem

## Problem Description
Verify graphically that the formulas in (6.11) have a maximum relative error of less than 1% in the range \( 0 < \zeta  < 1 \) .

$$
\frac{t_r}{t_n} \approx 0.16 + 0.14\zeta + 0.24\zeta^3,\quad
\frac{\tau}{t_n} \approx 0.19 + 0.1\zeta + 0.054\zeta^3
\tag{6.11}
$$
## Subproblems
1. Identify the specific formulas referenced as "(6.11)" for approximating time-domain specifications (likely rise time \(t_r\) and/or settling time \(t_s\)) of a second-order underdamped system.
2. Define the "relative error" metric by comparing the approximate formulas (6.11) to their exact analytical or numerical counterparts.
3. Determine the procedure for generating the graphical verification (plotting relative error vs. damping ratio \(\zeta\)).
4. Analyze the resulting plot(s) to find the maximum relative error value within \(0 < \zeta < 1\).
5. Conclude whether the maximum error is indeed less than 1%, thereby verifying the claim.

## Additional Information
- Equation (6.11), while not provided, is common in control systems textbooks. It typically provides approximate formulas for **rise time (\(t_r\))** and **settling time (\(t_s\))** for a second-order system with transfer function \( G(s) = \frac{\omega_n^2}{s^2 + 2\zeta\omega_n s + \omega_n^2} \).
- Common approximations are:
  - Rise time: \( t_r \approx \frac{1.8}{\omega_n} \) or a more accurate \(\zeta\)-dependent formula like \( t_r \approx \frac{0.8 + 2.5\zeta}{\omega_n} \).
  - Settling time (for 2% criterion): \( t_s \approx \frac{4}{\zeta \omega_n} \).
- "Relative error" is typically calculated as: \(\text{Relative Error} = \left| \frac{\text{Approximate Value} - \text{Exact Value}}{\text{Exact Value}} \right| \times 100\%\).
- The "exact" value for these specifications often requires numerical solution of transcendental equations (e.g., solving \( y(t) = 0.9 \) for rise time).
- Graphical verification involves plotting the relative error for each formula across the continuous range \(0 < \zeta < 1\) and observing its maximum.

## Constraints
- Verification must be performed **graphically** as stated in the problem.
- The analysis is confined to the underdamped range \(0 < \zeta < 1\).
- The conclusion must be based on the maximum observed error from the graph(s).

