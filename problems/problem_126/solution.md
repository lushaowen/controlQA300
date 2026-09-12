# Solution

## Method

\[
Q(s) = K_p \frac{s + \frac{b}{m}}{s + \frac{p}{m} K_p}.
\]

Assuming zero initial conditions, the response to a constant input is

\[
\bar{Y}(s) = \frac{\bar{y}}{s}
\]

is

\[
U(s) = Q(s)\bar{Y}(s) = \bar{y} K_p \frac{s + \frac{b}{m}}{s \left( s + \frac{p}{m} K_p \right)}.
\]

Expanding in partial fractions:

\[
\bar{y} K_p \frac{s + \frac{b}{m}}{s \left( s + \frac{p}{m} K_p \right)}
= \frac{\bar{y} b}{p} \left( \frac{1}{s} + \frac{\frac{p K_p}{b} - 1}{s + \frac{p}{m} K_p} \right)
\]

from which

\[
u(t) = \frac{\bar{y} b}{p}
\left( 1 + \left( \frac{p K_p}{b} - 1 \right) e^{-\frac{p}{m} K_p t} \right)
\]

which is maximized at \( t = 0 \), that is at

\[
u(0) = \frac{\bar{y} b}{p} \left( \frac{p K_p}{b} - 1 \right) = \bar{y} K_p.
\]

## Teaching Points

1. Step-response analysis using Laplace transforms
2. Role of poles in shaping transient behavior
3. Partial fraction expansion for inverse Laplace transforms
4. Identification of peak control effort
5. Interpretation of controller gain effects on input magnitude
