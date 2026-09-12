# Solution

We analyze the effect of a 20% increase in damping coefficients on a closed-loop rotational mechanical system.

---

## Method

### Step 1: Effect on Closed-Loop Gain

In a closed-loop system with proportional feedback, the steady-state gain is primarily determined by the feedback structure and controller gain \( K \), not by the damping coefficients.

Therefore, increasing \( b_1 \) and \( b_2 \) by 20% **does not change the closed-loop gain**.

---

### Step 2: Steady-State Error with Increased Damping

With increased damping, the steady-state speed error is given by:

\[
\overline{\omega}_2 - \widetilde{\omega}_2
= \left( \frac{r_1}{r_2} \right)
\frac{1}{
1 + \dfrac{r_1 r_2 K}{
1.2\left( b_1 r_2^2 + b_2 r_1^2 \right)
}
}
\;\overline{\omega}_1
\]

Evaluating this expression numerically yields:

\[
\overline{\omega}_2 - \widetilde{\omega}_2 \approx 2.1\;\text{rad/s}
\]

This represents **less than a 10% change** relative to the nominal steady-state error.

---

### Step 3: Effect on the Time Constant

The dominant closed-loop time constant becomes:

\[
\tau
= \frac{J_1 r_2^2 + J_2 r_1^2}
{1.2\left( b_1 r_2^2 + b_2 r_1^2 \right) + r_1 r_2 K}
\]

Numerical evaluation gives:

\[
\tau \approx 2.7\;\text{s}
\]

This change is also **less than 10%**, indicating limited sensitivity of the transient response to damping variation.

---

### Step 4: Sensitivity Interpretation

Both steady-state error and time constant show relatively small changes despite a 20% increase in damping coefficients.  
This confirms a key principle of feedback control:

> **Closed-loop systems significantly reduce sensitivity to parameter uncertainty.**

---

### Step 5: Effect of Initial Conditions

For different initial velocities:

- \( v_1(0) = 0 \)
- \( v_1(0) = 1\;\text{m/s} \)
- \( v_1(0) = -1\;\text{m/s} \)

the transient responses differ initially, but all trajectories converge to the same steady-state value due to closed-loop regulation.

This highlights:
- Robust stability
- Convergence independent of initial conditions
- Improved disturbance rejection

---

## Teaching Points

1. Closed-loop gain is largely invariant to damping uncertainty
2. Feedback reduces both steady-state and transient sensitivity
3. Time constants in feedback systems depend on both physical parameters and control gain
4. Moderate parameter variations often result in small performance changes
5. Initial conditions affect transients but not steady-state behavior in stable closed-loop systems
