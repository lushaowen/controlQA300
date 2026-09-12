# Solution

## Method

With knowledge of the stall torque, \( \tau \) , and the motor resistance, \( {R}_{a} \) , we determine

\[
{K}_{t} = \frac{{R}_{a}\tau }{{v}_{a}} = \frac{{0.2} \times  {1.2}}{12} \approx  {0.02}\frac{\mathrm{N}\mathrm{m}}{\mathrm{A}}
\]

and from P2.42 \( {K}_{e} = {K}_{t} = {0.02}\mathrm{\;V}\mathrm{\;s}/\mathrm{{rad}} \) .

Since \( \beta \) is already known we calculate

\[
J = \frac{{K}_{t}}{\beta {R}_{a}} = \frac{0.02}{{436.3} \times  {0.2}} \approx  {229.1} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}
\]

and

\[
b = {\alpha J} - \frac{{K}_{t}{K}_{e}}{{R}_{a}} = {10} \times  {229.1} \times  {10}^{-6} - \frac{{0.02}^{2}}{0.2} \approx  {291.8} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s}.
\]
## Teaching Points

1. Stall conditions eliminate back-emf and simplify motor modeling.
2. Stall torque provides a direct method for identifying the torque constant.
3. Electrical and mechanical parameters are strongly coupled in DC motor dynamics.
4. Parameter estimation relies on physically meaningful operating conditions.
5. Proper unit consistency is critical in electromechanical systems.
