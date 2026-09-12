# Solution

## Methon
 At the inertia \( J_1 \)

\[J_1 \dot{\omega}_1 = \tau + f_1 r_1 - f_2 r_1,\]

and at the inertia \( J_2 \)

\[J_2 \dot{\omega}_2 = f_2 r_2 - f_1 r_2.\]

Since the inertias are coupled by a belt, the linear speeds must be the same:

\[\omega_1 r_1 = \omega_2 r_2 \quad \implies \quad \omega_2 = (r_1 / r_2) \omega_1.\]

Multiplying the first equation by \( r_2 \) and the second by \( r_1 \) we obtain

\[r_2 J_1 \dot{\omega}_1 = r_2 \tau + f_1 r_1 r_2 - f_2 r_1 r_2,\]
\[r_1 J_2 \dot{\omega}_2 = f_2 r_1 r_2 - f_1 r_1 r_2.\]

Adding these together:

\[r_2 J_1 \dot{\omega}_1 + r_1 J_2 \dot{\omega}_2 = r_2 \tau.\]

Substituting \( \omega_2 = (r_1 / r_2) \omega_1 \):

\[r_2 J_1 \dot{\omega}_1 + r_1^2 / r_2 J_2 \dot{\omega}_1 = r_2 \tau,\]

and multiplying by \( r_2 \)

\[(J_1 r_2^2 + J_2 r_1^2) \dot{\omega}_1 = r_2^2 \tau.\]

## Teaching Points
1. Kinematic constraints reduce system order.
2. Force/torque transmission cancels internal variables.
3. Reflected inertia depends on geometry squared.
4. Ideal belt assumptions simplify dynamics significantly.
