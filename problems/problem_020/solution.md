# Solution

## Method
At the inertia \( {J}_{1} \)

\[
{J}_{1}{\dot{\omega }}_{1} + {b}_{1}{\omega }_{1} = \tau  + r\left( {{f}_{1} - {f}_{2}}\right)
\]

and at the inertia \( {J}_{2} \)

\[
{J}_{2}{\dot{\omega }}_{2} + {b}_{2}{\omega }_{2} = r\left( {{f}_{4} - {f}_{3}}\right) .
\]

Since the inertias are coupled by a belt, the linear speeds must be the same, that is

\[
{\omega }_{1}r = {\omega }_{2}r\; \Rightarrow  \;{\omega }_{2} = {\omega }_{1} = \omega
\]

Similarly

\[
{v}_{1} = {\omega r},\;{v}_{2} =  - {\omega r}
\]

so that at the masses

\[
r{m}_{1}\dot{\omega } = {m}_{1}{\dot{v}}_{1} = {m}_{1}g + {f}_{3} - {f}_{1},
\]

\[
r{m}_{2}\dot{\omega } =  - {m}_{2}{\dot{v}}_{2} =  - {m}_{2}g + {f}_{2} - {f}_{4}.
\]

Multiplying the last two equations by \( r \) and adding to the first two equations we obtain

\[
\left( {{J}_{1} + {J}_{2} + {r}^{2}{m}_{1} + {r}^{2}{m}_{2}}\right) \dot{\omega } + \left( {{b}_{1} + {b}_{2}}\right) \omega  = \tau  + {gr}\left( {{m}_{1} - {m}_{2}}\right) .
\]


## Teaching Points

1. Mechanical systems with belts can be reduced to a single-coordinate model
2. Translational masses contribute to effective rotational inertia
3. Gravity appears as an external disturbance torque
4. Counterweights reduce actuator effort and energy usage
5. Proper physical modeling simplifies control system design
