# Solution

We derive and analyze the closed-loop dynamics of the rotating machine under proportional feedback control.

---

## Method

### Step 1: Closed-Loop Model Derivation

From P2.12, the reduced-order plant model is:
\[
\left( J_1 r_2^2 + J_2 r_1^2 \right) \dot{\omega}_1
+\left( b_1 r_2^2 + b_2 r_1^2 \right) \omega_1
= r_2^2 \tau.
\]

The feedback control law is:
\[
\tau = K(\overline{\omega}_2 - \omega_2)
= \left( \frac{r_1}{r_2} \right) K (\overline{\omega}_1 - \omega_1),
\]
where
\[
\overline{\omega}_1 = \left( \frac{r_2}{r_1} \right) \overline{\omega}_2.
\]

Substituting the controller into the plant yields the closed-loop equation:
\[
\left( J_1 r_2^2 + J_2 r_1^2 \right) \dot{\omega}_1
+\left( b_1 r_2^2 + b_2 r_1^2 + r_1 r_2 K \right) \omega_1
=r_1 r_2 K \overline{\omega}_1.
\]

---

### Step 2: Closed-Loop Solution

The solution of the first-order closed-loop system is:
\[
\omega_1(t)
= \widetilde{\omega}_1 \left( 1 - e^{\lambda t} \right)
+\omega_1(0) e^{\lambda t},
\]
where
\[
\widetilde{\omega}_1
= \frac{r_1 r_2 K \overline{\omega}_1}
{b_1 r_2^2 + b_2 r_1^2 + r_1 r_2 K},
\]
\[
\lambda
= -\frac{b_1 r_2^2 + b_2 r_1^2 + r_1 r_2 K}
{J_1 r_2^2 + J_2 r_1^2}.
\]

The output angular velocity is:
\[
\omega_2(t) = \left( \frac{r_1}{r_2} \right) \omega_1(t).
\]

---

### Step 3: Gain Selection for Desired Time Constant

The closed-loop time constant is:
\[
\tau_c = -\lambda^{-1}
= \frac{J_1 r_2^2 + J_2 r_1^2}
{b_1 r_2^2 + b_2 r_1^2 + r_1 r_2 K}.
\]

Setting \( \tau_c = 3~\mathrm{s} \) and using data from P2.13:
\[
K
= \frac{(J_1 r_2^2 + J_2 r_1^2)/\tau_c
-(b_1 r_2^2 + b_2 r_1^2)}
{r_1 r_2}
\approx 0.23.
\]

---

### Step 4: Comparison with Open-Loop System

The open-loop time constant is:
\[
\tau_{\text{OL}}
= \frac{J_1 r_2^2 + J_2 r_1^2}
{b_1 r_2^2 + b_2 r_1^2}
\approx 6.4~\mathrm{s}.
\]

Thus, feedback control approximately halves the response time.

---

### Step 5: Steady-State Error

The steady-state tracking error is:
\[
\overline{\omega}_2 - \widetilde{\omega}_2
= \left( \frac{r_1}{r_2} \right)
\frac{b_1 r_2^2 + b_2 r_1^2}
{b_1 r_2^2 + b_2 r_1^2 + r_1 r_2 K}
\overline{\omega}_1.
\]

This shows that:
- The steady-state error is nonzero.
- Increasing \( K \) reduces but does not eliminate the error.

---

## Teaching Points
1. Proportional feedback improves speed of response.
2. Closed-loop systems are less sensitive to parameter uncertainty.
3. Time constant is directly shaped by feedback gain.
4. P control cannot eliminate steady-state error.
5. Integral action is required for perfect tracking.
