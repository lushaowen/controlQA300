# Solution


## Method

 To solve the differential equation using the Laplace transform we assume zero-initial conditions and calculate

\[
\left( {{ms} + b}\right) V\left( s\right)  = m\mathcal{L}\{ \dot{v}\}  + b\mathcal{L}\{ v\}  = \mathcal{L}\{ {mg}\}  = \frac{mg}{s}
\]

from which

\[
V\left( s\right)  = \frac{mg}{s\left( {{ms} + b}\right) } = \frac{g}{s\left( {s + b/m}\right) } = \frac{mg}{b}\left( {\frac{1}{s} - \frac{1}{s + b/m}}\right)  = \frac{\beta }{s\left( {s + \alpha }\right) },
\]

where

\[
\alpha  = \frac{b}{m},\;\beta  = g.
\]

Expanding in partial fractions

\[
\frac{\beta }{s\left( {s + \alpha }\right) } = \frac{\beta }{\alpha }\left( {\frac{1}{s} + \frac{1}{s + \alpha }}\right) \tag{C.1}
\]

from which

\[
{\mathcal{L}}^{-1}\left\{  {\frac{\beta }{\alpha }\left( {\frac{1}{s} + \frac{1}{s + \alpha }}\right) }\right\}   = \frac{\beta }{\alpha }\left( {1 - {e}^{-{\alpha t}}}\right) ,\;t \geq  0, \tag{C.2}
\]

so that

\[
v\left( t\right)  = \frac{mg}{b}\left( {1 - {e}^{-\left( {b/m}\right) t}}\right) ,\;t \geq  0.
\]

If we treat \( u = {mg} \) as an input

\[
m\mathcal{L}\{ \dot{v}\}  + b\mathcal{L}\{ v\}  = \left( {{ms} + b}\right) V\left( s\right)  = U\left( s\right) \mathcal{L}\{ u\}
\]

and

\[
V\left( s\right)  = G\left( s\right) U\left( s\right) ,\;G\left( s\right)  = \frac{\beta }{s + \alpha },\;\alpha  = \frac{b}{m},\;\beta  = \frac{1}{m}.
\]

From velocity to position we apply the integration property to obtain:

\[
X\left( s\right)  = \mathcal{L}\{ x\}  = \mathcal{L}\left\{  {{\int }_{0}^{t}v\left( \tau \right) {d\tau }}\right\}   = \frac{V\left( s\right) }{s}
\]

and

\[
X\left( s\right)  = \frac{V\left( s\right) }{s} = H\left( s\right) U\left( s\right) ,\;H\left( s\right)  = \frac{G\left( s\right) }{s} = \frac{\beta }{s\left( {s + \alpha }\right) }.
\]

If all constants are positive, \( G\left( s\right) \) is asymptotically stable but \( H\left( s\right) \) is not since 0 is one of its roots.

## Teaching Points
1. **First-Order System Response**: The velocity of an object with linear resistance follows a standard first-order lag response, approaching a terminal velocity $mg/b$.
2. **Transfer Function Derivation**: Transfer functions represent the ratio of output to input in the $s$-domain, independent of the specific input signal (like $mg$).
3. **The Integrator Property**: Moving from velocity to position introduces a pole at the origin ($1/s$), which typically changes the stability category of the system.
4. **Asymptotic Stability**: Requires all poles to be in the Left Half Plane (LHP). A pole at $s=0$ allows the output to stay constant or grow, violating the "decay to zero" requirement for asymptotic stability.