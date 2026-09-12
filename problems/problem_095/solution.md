# Solution

## Method

Following the block diagram

\[
Y\left( s\right)  = U\left( s\right)  + \alpha {e}^{-{sT}}Y\left( s\right)
\]

or

\[
Y\left( s\right)  = \frac{U\left( s\right) }{1 - \alpha {e}^{-{sT}}}.
\]

When \( \alpha  = 1 \) this is exactly the same transfer-function as in P3.48. As in P3.48

\[
Y\left( s\right)  = \frac{U\left( s\right) }{1 - \alpha {e}^{-{sT}}} = \mathop{\sum }\limits_{{k = 0}}^{\infty }{\alpha }^{k}U\left( s\right) {e}^{-{skT}}
\]

for all \( s \) such that \( \left| {e}^{-{sT}}\right|  < {\alpha }^{-1} \) and

\[
y\left( t\right)  = \mathcal{L}\{ Y\left( s\right) \}  = \mathop{\sum }\limits_{{k = 0}}^{\infty }{\mathcal{L}}^{-1}\left\{  {{\alpha }^{k}U\left( s\right) {e}^{-{skT}}}\right\}   = \mathop{\sum }\limits_{{k = 0}}^{\infty }{\alpha }^{k}u\left( {t - {kT}}\right) .
\]

When \( \left| \alpha \right|  < 1 \) the effect of past periods decreases as time grows. Conversely, when \( \left| \alpha \right|  > 1 \) the effect of past periods increases as time grows.

In terms of the impulse response

\[
g\left( t\right)  = \mathcal{L}\{ G\left( s\right) \}  = \mathcal{L}\left\{  {\left( 1 - \alpha {e}^{-{sT}}\right) }^{-1}\right\}   = \mathop{\sum }\limits_{{k = 0}}^{\infty }{\mathcal{L}}^{-1}\left\{  {{\alpha }^{k}{e}^{-{skT}}}\right\}   = \mathop{\sum }\limits_{{k = 0}}^{\infty }{\alpha }^{k}\delta \left( {t - {kT}}\right)
\]

so that

\[
{\int }_{{0}^{ - }}^{\infty }\left| {g\left( t\right) }\right| {dt} = \left| {\mathop{\sum }\limits_{{k = 0}}^{\infty }{\alpha }^{k}{\int }_{{0}^{ - }}^{\infty }\delta \left( {t - {kT}}\right) {dt}}\right|  = \left| {\mathop{\sum }\limits_{{k = 0}}^{\infty }{\alpha }^{k}}\right| .
\]

This series converge when \( \left| \alpha \right|  < 1 \) , in which case

\[
{\int }_{{0}^{ - }}^{\infty }\left| {g\left( t\right) }\right| {dt} = {\left( \left| 1 - \alpha \right| \right) }^{-1}.
\]

Otherwise, if \( \left| \alpha \right|  \geq  1 \) it diverges.


## Teaching Points
1. **Feedback with Delay**: Systems with feedback delays can be represented as infinite sums of delayed signals.
2. **Geometric Series in S-Domain**: The expansion $(1-x)^{-1}$ is a powerful tool for analyzing repetitive or delayed systems.
3. **Stability Criterion**: For systems with impulsive components, asymptotic stability requires the absolute sum of the impulse strengths to be finite.
4. **Parameter Sensitivity**: The stability of this system depends entirely on the feedback gain $\alpha$ regardless of the delay time $T$.