# Solution

## Method

Recall that the transfer function of the one-eighth car model is

\[
G(s) = \frac{-s^{2}}{s^{2} + \frac{b}{m}s + \frac{k}{m}},
\]

which has a complex conjugate pole pair at \( s = -1.26 \pm 15.66j \). This results in the Bode plot shown in Figure G.16. The Bode magnitude plot peaks at

\[
\omega = \omega_{n}\sqrt{1 - 2\zeta^{2}} = 1.5607 \times 10^{4}\,\mathrm{rad/s}.
\]

We can also compute the peak magnitude in decibels. For a second-order system of the form

\[
H(s) = \frac{\omega_{n}^{2}}{s^{2} + 2\xi \omega_{n}s + \omega_{n}^{2}},
\]

the peak magnitude is given by

\[
20\log_{10}\left( 2\xi\sqrt{1 - \xi^{2}} \right).
\]

For \( \xi = 0.08 \), the peak magnitude is \( -31.8993\,\mathrm{dB} \).

Since the given transfer function does not include an \( \omega_{n}^{2} \) term in the numerator, we must multiply the above expression by \( \omega_{n}^{2} \). Furthermore, the system contains a double zero at the origin, contributing an additional \( 40\,\mathrm{dB/dec} \) slope. Accounting for this yields a peak magnitude of

\[
-31.8993 + 40 + 40\log_{10}(\omega / 10) = 15.83\,\mathrm{dB}.
\]

The resulting Bode magnitude and phase plots are shown in Figure G.16.

## Teaching Points

1. Interpretation of resonance in lightly damped second-order systems
2. Relationship between natural frequency and resonant frequency
3. Effect of damping ratio on peak magnitude
4. Influence of zeros at the origin on Bode magnitude slope
5. Use of Bode plots to assess vibration amplification
6. Frequency-domain interpretation of vehicle ride dynamics
