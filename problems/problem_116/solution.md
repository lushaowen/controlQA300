# Solution

## Method
Assuming zero initial conditions, in the case of a constant voltage we set

\[
V\left( s\right)  = \frac{\widetilde{v}}{s}
\]

and calculate

\[
{V}_{c}\left( s\right)  = G\left( s\right) V\left( s\right)  = \frac{\beta }{s + \alpha }\frac{\widetilde{v}}{s},
\]

where \( \alpha  = \beta  = 1/{RC} \) are as in P3.80. Expanding in partial fractions as in (C.1):

\[
{V}_{c}\left( s\right)  = G\left( s\right) T\left( s\right)  = \frac{\beta \widetilde{v}}{\alpha }\left( {\frac{1}{s} - \frac{1}{s + \alpha }}\right)  = \widetilde{v}\left( {\frac{1}{s} - \frac{1}{s + \alpha }}\right)
\]

and from (C.2):

\[
{v}_{c}\left( t\right)  = \widetilde{v}\left( {1 - {e}^{-{\alpha t}}}\right) ,\;t \geq  0.
\]

The transient and steady-state components are

\[
{v}_{ctr}\left( t\right)  =  - \widetilde{v}{e}^{\lambda t},
\]

\[
{v}_{\mathrm{{css}}}\left( t\right)  = \widetilde{v}\text{ . }
\]

## Teaching Points
1. Step response of a first-order linear system
2. Use of partial fraction expansion in inverse Laplace transforms
3. Identification of transient versus steady-state behavior
4. Physical interpretation of exponential decay in RC circuits
5. Role of the time constant in determining response speed
