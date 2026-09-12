# Problem

## Problem Description
Assume that \( F\left( s\right) \) satisfies (3.26). Show that if \( t < 0 \) then

\[
\left| {{\int }_{{C}_{ + }^{\rho }}F\left( s\right) {e}^{st}{ds}}\right|  \leq  \frac{{\pi M}{e}^{\alpha t}}{\left| t\right| {\left( \rho  - \left| \alpha \right| \right) }^{k}}.
\]

Use this inequality to prove (3.27)

\[\lim_{\rho \to \infty} \int_{C_+^t} F(s)e^{st} \, ds = 0, \quad t < 0.
\tag{3.27}\]

## Subproblems
1. Parametrize the contour integral and apply the integral magnitude inequality.
2. Utilize the bound for $|F(s)e^{st}|$ derived previously (from Problem 3.28) to simplify the integrand.
3. Apply the integral inequality for $\int e^{-R \cos \theta} d\theta$ (from Problem 3.27) by identifying the appropriate constant $R$ for the case $t < 0$.
4. Perform the limit analysis as $\rho \to \infty$ to show the integral vanishes.

## Additional Information
- The parameter $\alpha$ is a real constant.
- The time variable $t$ is strictly negative ($t < 0$).
- Use the results:
    - Result A: $|F(s)e^{st}| \leq \frac{M e^{\alpha t}}{(\rho - |\alpha|)^k} e^{\rho t \cos \theta}$
    - Result B: $\int_{-\pi/2}^{\pi/2} e^{-R \cos \theta} d\theta < \frac{\pi}{R}$ for $R > 0$.

## Constraints
- All steps of the derivation must be explicitly shown.
- The use of previous lemmas (Result A and Result B) must be clearly indicated.
- The limit argument must account for the power $k > 0$.