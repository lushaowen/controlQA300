# Solution

## Method

Because there are no pole-zero cancelations in the product \( GK \) and

\[
S = \frac{1}{1 + GK}
= \frac{1}{1 + \frac{1}{s(s + 1)}}
= \frac{s(s + 1)}{s^2 + s + 1},
\]

\[
H = GKS = \frac{1}{s^2 + s + 1}
\]

has poles at
\( s \approx \{ -0.5 \pm 0.87j \} \),
\( S \) is asymptotically stable and the closed-loop is internally stable.

The steady-state component of the output is given by

\[
y_{\mathrm{ss}}(t)
= \bar{y} H(j0)
-\bar{v} H(j0)
-|H(j\omega)| \cos\!\left( \omega t + \angle H(j\omega) \right),
\]

where

\[
H(j0) = 1,\;
H(j\omega) = \frac{1}{j\omega + 1 - \omega^2}
= \frac{1}{\sqrt{\omega^2 + (1 - \omega^2)^2}}
\tan^{-1}\frac{-\omega}{1 - \omega^2}.
\]

That is

\[
y_{\mathrm{ss}}(t)
= \bar{y} - \bar{v}
-\frac{1}{\sqrt{\omega^2 + (1 - \omega^2)^2}}
\cos\!\left(
\omega t - \tan^{-1}\!\frac{\omega}{1 - \omega^2}
\right).
\]

If \( \bar{v} \neq 0 \), the closed-loop system does not track the reference input
\( \bar{y}(t) \) and does not reject the sensor noise \( v \).
However, when \( \omega \to \infty \) and \( \bar{v} = 0 \),

\[
y_{\mathrm{ss}}(t) = \bar{y}.
\]

## Teaching Points

1. Effect of integrators on reference tracking
2. Measurement noise propagation through closed-loop systems
3. Frequency-dependent noise attenuation
4. Difference between constant bias and oscillatory noise
5. High-frequency roll-off properties of closed-loop transfer functions
