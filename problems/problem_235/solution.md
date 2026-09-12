# Solution

## Method

The relationship

\[
m\ddot{z} = u - m\ddot{y}, \quad u = -\left(kz + b\dot{z}\right)
\]

follows directly from the differential equation of the system. This interpretation treats the term \( -m\ddot{y} \) as an input disturbance, with the system and controller transfer functions given by

\[
G(s) = \frac{1}{s^{2}}, \quad K(s) = \frac{b}{m}(s + z), \quad z = \frac{k}{b}.
\]

The open-loop zero is placed at

\[
z = \frac{k}{b} = 100.
\]

The corresponding Bode plots and Nyquist diagram are shown in Figure G.17. As observed from the Nyquist diagram, no point on the negative real axis is encircled. Since the open-loop transfer function has no poles in the right-half plane, asymptotic stability of the closed-loop system is guaranteed for any \( m > 0 \).

Selecting \( m = 640\,\mathrm{kg} \), the gain margin is infinite and the phase margin is \( 90.6^\circ \).

## Teaching Points

1. Interpretation of mechanical parameters as controller gains
2. Reformulation of physical systems as PD-controlled plants
3. Disturbance modeling in acceleration-driven systems
4. Application of Nyquist criterion to systems without RHP poles
5. Interpretation of infinite gain margin
6. Robustness implications of large phase margins
