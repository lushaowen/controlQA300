# Solution

## Method
Use the given equations to write:

\[
v = {R}_{1}{i}_{{R}_{1}}
\]

\[
= {R}_{1}\left( {{i}_{{C}_{2}} - {i}_{{C}_{1}}}\right)
\]

\[
=  - {R}_{1}{C}_{2}{\dot{v}}_{o} - {R}_{1}{C}_{1}\dot{v}
\]

which is the desired equation.

The solution to the auxiliary equation is

\[
z\left( t\right)  = z\left( 0\right)  - \frac{1}{{R}_{1}{C}_{2}}{\int }_{0}^{t}v\left( \tau \right) {d\tau }
\]

and

\[
{v}_{o}\left( t\right)  = {R}_{1}{C}_{1}\dot{z}\left( t\right)  + z\left( t\right) ,
\]

\[
= z\left( 0\right)  - \frac{{C}_{1}}{{C}_{2}}v\left( t\right)  - \frac{1}{{R}_{1}{C}_{2}}{\int }_{0}^{t}v\left( \tau \right) {d\tau }.
\]

Multiplying by \( {R}_{1}{C}_{2} \) and differentiating under the integral

\[
{R}_{1}{C}_{2}{\dot{v}}_{o}\left( t\right)  =  - {R}_{1}{C}_{1}\dot{v} - v\left( t\right) .
\]

## Teaching Points

1. Ideal Op-Amp assumptions greatly simplify circuit modeling
2. Kirchhoff’s current law enables reduction to a single differential equation
3. Auxiliary variables can be introduced to simplify system representations
4. Integral and differential relations naturally arise in RC circuits
5. This circuit structure is closely related to dynamic compensators in control systems
