# Solution

## Method
Assuming zero initial conditions and treating \( w = {gr}\left( {{m}_{1} - {m}_{2}}\right) \) as an input we calculate

\[
\left( {{Js} + \left( {{b}_{1} + {b}_{2}}\right) }\right) \Omega \left( s\right)  = J\mathcal{L}\{ \dot{\omega }\}  + \left( {{b}_{1} + {b}_{2}}\right) \mathcal{L}\{ \omega \}  = \mathcal{L}\{ \tau  + w\}  = T\left( s\right)  + W\left( s\right) ,
\]

and

\[
{V}_{1}\left( s\right)  = \mathcal{L}\left\{  {v}_{1}\right\}   = r\mathcal{L}\{ \omega \}  = {r\Omega }\left( s\right)
\]

from which

\[
{V}_{1}\left( s\right)  = {G}_{\tau }\left( s\right) T\left( s\right)  + {G}_{w}W\left( s\right) ,\;{G}_{\tau }\left( s\right)  = {G}_{w}\left( s\right)  = G\left( s\right)  = \frac{\beta }{s + \alpha },
\]

where

\[
\alpha  = \frac{{b}_{1} + {b}_{2}}{{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) },\;\beta  = \frac{r}{{J}_{1} + {J}_{2} + {r}^{2}\left( {{m}_{1} + {m}_{2}}\right) }.
\]

If all constants are positive then \( \alpha  > 0 \) and these transfer-functions are asymptotically stable.

## Teaching Points
1. Modeling mechanical systems using equivalent rotational dynamics.
2. Interpretation of gravity as an external disturbance input.
3. Derivation of multiple transfer functions from a single state equation.
4. Relationship between angular and linear motion through kinematic constraints.
5. First-order system dynamics and pole-based stability analysis.
6. Physical meaning of asymptotic stability in elevator systems.
