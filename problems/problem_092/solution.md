# Solution


## Method

The transfer function is

\[
G\left( s\right)  = \mathcal{L}\{ g\left( t\right) \}  = \frac{1}{s + 1},
\]

which is of order 1; the system is asymptotically stable because the pole \( s =  - 1 \) is negative; the response to a step input is

\[
y\left( t\right)  = {\mathcal{L}}^{-1}\left\{  {\widetilde{u}{s}^{-1}G\left( s\right) }\right\}   = {\mathcal{L}}^{-1}\left\{  \frac{\widetilde{u}}{s\left( {s + 1}\right) }\right\}   = \widetilde{u}{\mathcal{L}}^{-1}\left\{  {\frac{1}{s} - \frac{1}{s + 1}}\right\}   = \widetilde{u}\left( {1 - {e}^{-t}}\right)
\]

The transient and steady-state components are:

\[
{y}_{\mathrm{{tr}}}\left( t\right)  =  - \widetilde{u}{e}^{-t},\;{y}_{\mathrm{{ss}}}\left( t\right)  = \widetilde{u}.
\]

## Teaching Points
1. The impulse response uniquely determines the transfer function of an LTI system
2. System order corresponds to the number of poles in the transfer function
3. Pole locations determine stability properties
4. Step responses of first-order systems exhibit exponential transients
5. Steady-state behavior is obtained by evaluating the limit as \( t \to \infty \)
6. Transient terms decay exponentially in asymptotically stable systems
