# Solution
## Methods
If \( u\left( t\right)  = \left( {b/p}\right) \bar{y} \) and \( w\left( t\right)  = \bar{w} \) then

\[
\dot{y}\left( t\right)  + \frac{b}{m}y\left( t\right)  = \frac{p}{m}u\left( t\right)  + \frac{p}{m}w\left( t\right)  = \frac{b}{m}\bar{y} + \frac{p}{m}\bar{w}
\]

and

\[
y\left( t\right)  = \widetilde{y}\left( {1 - {e}^{\lambda t}}\right)  + {y}_{0}{e}^{\lambda t}
\]

where

\[
\lambda  =  - \frac{b}{m},\;\widetilde{y} = \bar{y} + \frac{p}{b}\bar{w} = \bar{y} + G\left( 0\right) \bar{w}.
\]

Consequently with \( {y}_{0} = \bar{y} \)

\[
y\left( t\right)  = \left( {\bar{y} + G\left( 0\right) \bar{w}}\right) \left( {1 - {e}^{-\left( {b/m}\right) t}}\right)  + \bar{y}{e}^{-\left( {b/m}\right) t} = \bar{y} + \left( {1 - {e}^{-\left( {b/m}\right) t}}\right) G\left( 0\right) \bar{w}
\]

and

\[
{\Delta y}\left( t\right)  = y\left( t\right)  - {y}_{0} = y\left( t\right)  - \bar{y} = \left( {1 - {e}^{-\left( {b/m}\right) t}}\right) G\left( 0\right) \bar{w}.
\]

## Teaching Points
1. Open-loop systems respond directly to disturbances
2. First-order systems exhibit exponential transient behavior
3. Steady-state gain determines long-term response
4. Initial conditions affect only the transient component

## Common Mistakes
- Incorrect substitution of steady-state input
- Sign errors in the exponential term
- Confusing transient and steady-state responses
- Forgetting to subtract the initial condition
