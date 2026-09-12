# Solution

## Method

**For (6.15)**

The modified plant is given by:
\[
\widetilde{G} = \frac{G}{1 + s{K}_{d}G}
\]

The closed-loop transfer function `H` is:
\[
H = \frac{{K}_{p}\widetilde{G}}{1 + {K}_{p}\widetilde{G}}
\]

Substitute `\widetilde{G}`:
\[
H = \frac{{K}_{p}\frac{G}{1 + s{K}_{d}G}}{1 + {K}_{p}\frac{G}{1 + s{K}_{d}G}}
\]

Combine terms in the denominator (1 = `(1 + sK_d G)/(1 + sK_d G)`):
\[
H = \frac{{K}_{p}G}{1 + s{K}_{d}G + {K}_{p}G}
\]
\[
= \frac{{K}_{p}G}{1 + \left( {{K}_{p} + s{K}_{d}}\right) G}
\]

Now, express `G` as `N_L / D_L`:
\[
H = \frac{{K}_{p}\frac{{N}_{L}}{{D}_{L}}}{1 + \left( {{K}_{p} + s{K}_{d}}\right) \frac{{N}_{L}}{{D}_{L}}}
\]

Multiply numerator and denominator by `D_L`:
\[
H = \frac{{K}_{p}{N}_{L}}{{D}_{L} + \left( {{K}_{p} + s{K}_{d}}\right) {N}_{L}}
\]

**For (6.16)**

The closed-loop transfer function `H` for this configuration is:
\[
H = \frac{\left( {{K}_{p} + s{K}_{d}}\right) G}{1 + \left( {{K}_{p} + s{K}_{d}}\right) G}
\]

Substitute `G = N_L / D_L`:
\[
H = \frac{\left( {{K}_{p} + s{K}_{d}}\right) \frac{{N}_{L}}{{D}_{L}}}{1 + \left( {{K}_{p} + s{K}_{d}}\right) \frac{{N}_{L}}{{D}_{L}}}
\]

Multiply numerator and denominator by `D_L`:
\[
H = \frac{\left( {{K}_{p} + s{K}_{d}}\right) {N}_{L}}{{D}_{L} + \left( {{K}_{p} + s{K}_{d}}\right) {N}_{L}}.
\]

## Teaching Points
1. **Block Diagram Algebra**: Demonstrates how to derive closed-loop transfer functions from different arrangements of a PD controller and a plant.
2. **Effect of Controller Placement**: Equation (6.15) shows the derivative term `sK_d` in a feedback path around the plant `G`, creating a modified plant `\widetilde{G}` before the proportional gain `K_p`. Equation (6.16) shows the PD controller `(K_p + sK_d)` acting directly on the error signal in the forward path. Both result in a characteristic equation of `D_L + (K_p + sK_d)N_L = 0`.
3. **Algebraic Manipulation**: Reinforces skills in simplifying complex rational expressions by finding common denominators and canceling terms.
4. **Standard Form**: Highlights the importance of expressing the final transfer function as a ratio of polynomials in `s` for analysis (e.g., stability, frequency response).