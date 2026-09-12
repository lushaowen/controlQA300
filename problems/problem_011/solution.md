# Solution

## Method
The solution to the first-order differential equation from P2.4 is

\[
v\left( t\right)  = \widetilde{v}\left( {1 - {e}^{\lambda t}}\right)  + v\left( 0\right) {e}^{-{\lambda t}},\;\lambda  =  - \frac{b}{m},\;\widetilde{v} = \frac{mg}{b}.
\]

If \( m = 1\mathrm{\;{kg}}, g = {10}\mathrm{\;m}/{\mathrm{s}}^{2}, b = {10}\mathrm{\;{kg}}/\mathrm{s} \) then

\[
\widetilde{v} = \frac{mg}{b} = 1\mathrm{\;m}/\mathrm{s},\;\lambda  =  - \frac{b}{m} =  - {10}{\mathrm{\;s}}^{-1}
\]

with which

\[
v\left( t\right)  = 1 + \left( {v\left( 0\right)  - 1}\right) {e}^{-{10t}}.
\]

The responses when \( v\left( 0\right)  = 0, v\left( 0\right)  = 1\mathrm{\;m}/\mathrm{s} \) , and \( v\left( 0\right)  =  - 1\mathrm{\;m}/\mathrm{s} \) should be as in the following plot:

\[
x\left( t\right)  = x\left( 0\right)  + {\int }_{0}^{t}v\left( \tau \right) {d\tau } = x\left( 0\right)  + {\int }_{0}^{t}1 + \left( {v\left( 0\right)  - 1}\right) {e}^{-{10\tau }}{d\tau }
\]

\[
= x\left( 0\right)  + t + \frac{\left( v\left( 0\right)  - 1\right) }{10}\left( {1 - {e}^{-{10t}}}\right) .
\]

![bo_d5ctcr3ef24c73bj2om0_10_313_496_779_250_0.jpg](images\bo_d5ctcr3ef24c73bj2om0_10_313_496_779_250_0.jpg)

## Teaching Points
1. First-order systems exhibit exponential convergence.
2. Steady-state velocity depends on force balance.
3. Initial conditions affect only transient behavior.
4. The time constant is determined by $m/b$.

## Common Mistakes
- Confusing $\lambda$ with $+b/m$ instead of $-b/m$.
- Forgetting the steady-state term.
- Assuming initial conditions affect steady-state.
- Mixing velocity and position responses.
