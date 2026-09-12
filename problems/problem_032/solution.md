# Solution


## Method
With Newton's second law help we write

\[
{m}_{1}{\ddot{x}}_{1} =  - b\left( {{\dot{x}}_{1} - {\dot{x}}_{2}}\right)  - k\left( {{x}_{1} - {x}_{2}}\right) ,
\]

\[
{m}_{2}{\ddot{x}}_{2} =  - b\left( {{\dot{x}}_{2} - {\dot{x}}_{1}}\right)  - k\left( {{x}_{2} - {x}_{1}}\right) .
\]

Because

\[
{x}_{1} = {y}_{1} + \frac{{m}_{2}}{M}{y}_{2},\;{x}_{2} = {y}_{1} - \frac{{m}_{1}}{M}{y}_{2},\;M = \frac{{m}_{1} + {m}_{2}}{2},
\]

we have

\[
{m}_{1}{\ddot{y}}_{1} + \frac{{m}_{1}{m}_{2}}{M}{\ddot{y}}_{2} =  - b{\dot{y}}_{2} - k{y}_{2},
\]

\[
{m}_{2}{\ddot{y}}_{1} - \frac{{m}_{1}{m}_{2}}{M}{\ddot{y}}_{2} = b{\dot{y}}_{2} + k{y}_{2}.
\]

Adding the two equations:

\[
M{\ddot{y}}_{1} = 0,
\]

and subtracting after multiplying the first equation by \( {m}_{2} \) and the second by \( {m}_{1} \) :

\[
{m}_{1}{m}_{2}{\ddot{y}}_{2} =  - \left( {{m}_{1} + {m}_{2}}\right) b{\dot{y}}_{2} - \left( {{m}_{1} + {m}_{2}}\right) k{y}_{2}
\]

which are "decoupled". The first equation is the dynamic of the center of mass \( \left( {{m}_{1}{x}_{1} + {m}_{2}{x}_{2}}\right) /M \) and the second is the dynamics of the body, which we expect to be decoupled from physics.


## Teaching Points

1. Symmetric internal forces cannot influence center-of-mass motion
2. Coordinate transformations can reveal physically meaningful modes
3. Center-of-mass and internal dynamics naturally decouple
4. Relative coordinates isolate deformation dynamics
5. Physics intuition guides effective mathematical modeling
