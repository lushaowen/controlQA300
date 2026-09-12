# Solution

## Method

This perturbation model may represent a day/night cycle. The approximation corresponds to assuming small fluctuations of the temperature around the average flow \( \bar{w} \) . If those fluctuations are not small the approximation might not hold.

Using the approximation and assuming \( {T}_{i} \) is constant

\[
\dot{T} + {\alpha T} = \beta \left( {q + \gamma  + {\delta w}}\right) ,
\]

where

\[
\alpha  = \frac{\bar{w}}{m} + \frac{1}{mcR},\;\beta  = \frac{1}{mc},\;\gamma  = \frac{1}{R}{T}_{o},\;\delta  = c{T}_{i}.
\]

As in P4.38, we have

\[
G\left( s\right)  = \frac{T\left( s\right) }{Q\left( s\right) } = \frac{\beta }{s + \alpha },\;K\left( s\right)  = K,
\]

which does not enable rejection of the modified input disturbance. With or without the approximation, the closed-loop system cannot asymptotically track the input disturbance. Doing so would require a controller with poles at \( s = 0 \) and \( s =  \pm  {j\omega } \) .

Selecting \( K = {342} \) as in P4.39, the closed-loop response should look like:

![bo_d5ctcr3ef24c73bj2om0_79_443_1417_786_247_0.jpg](images/bo_d5ctcr3ef24c73bj2om0_79_443_1417_786_247_0.jpg)

## Teaching Points

1. Periodic disturbances cannot be rejected by simple proportional control.
2. Integral action alone is insufficient for sinusoidal disturbance rejection.
3. Internal Model Principle explains the need for controller poles matching disturbance dynamics.
4. Approximations simplify analysis but do not change fundamental rejection limits.
5. Environmental cycles often introduce structured, non-constant disturbances.
