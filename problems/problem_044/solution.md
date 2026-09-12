# Solution


## Method

Kirchoff's voltage law for the circuit is:

\[
{v}_{a} = {R}_{a}{i}_{a} + {L}_{a}{\dot{i}}_{a} + {K}_{e}\omega
\]

The mechanical equation of motion is

\[
J\dot{\omega } + {b\omega } = \tau  = {K}_{t}{i}_{a}
\]

Multiplying by \( {R}_{a} \)

\[
J{R}_{a}\dot{\omega } + b{R}_{a}\omega  = \tau  = {K}_{t}{R}_{a}{i}_{a}
\]

and then by \( {L}_{a} \) and differentiating

\[
J{L}_{a}\ddot{\omega } + b{L}_{a}\dot{\omega } = {K}_{t}{L}_{a}{\dot{i}}_{a}
\]

so that

\[
J{L}_{a}\ddot{\omega } + \left( {b{L}_{a} + J{R}_{a}}\right) \dot{\omega } + b{R}_{a}\omega  = {K}_{t}\left( {{L}_{a}{\dot{i}}_{a} + {R}_{a}{i}_{a}}\right)
\]

\[
= {K}_{t}\left( {{v}_{a} - {K}_{e}\omega }\right)
\]

which is equal to the expression sought after rearranging.

When \( {L}_{a} = 0 \)

\[
J{R}_{a}\dot{\omega } + \left( {b{R}_{a} - {K}_{t}{K}_{e}}\right) \omega  = {K}_{t}{v}_{a}
\]

which is the equation obtained before multiplied by \( {R}_{a} \) .

## Teaching Points

1. Armature inductance introduces second-order dynamics into the motor model.
2. Electrical and mechanical subsystems interact through \( K_t \) and \( K_e \).
3. Neglecting \( L_a \) reduces the system order and simplifies analysis.
4. The full model is required for high-frequency or fast transient analysis.
5. Model assumptions directly affect system dynamics and accuracy.
