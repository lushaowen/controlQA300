# Solution

## Method

The solution to the first-order differential equation from P2.12 when \( \tau  = \overline{\tau } \) is constant is

\[
{\omega }_{1}\left( t\right)  = {\widetilde{\omega }}_{1}\left( {1 - {e}^{\lambda t}}\right)  + {\omega }_{1}\left( 0\right) {e}^{-{\lambda t}},
\]

where

\[
\lambda  =  - \frac{{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}{{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}},\;{\widetilde{\omega }}_{1} = \frac{{r}_{2}^{2}}{{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\overline{\tau }.
\]

If \( \tau  = 1\mathrm{\;N}\mathrm{\;m},{r}_{1} = {25}\mathrm{\;{mm}},{r}_{2} = {500}\mathrm{\;{mm}},{b}_{1} = {0.01}\mathrm{{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{b}_{2} = {0.1}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s},{J}_{1} = {0.0031}\mathrm{\;{kg}}{\mathrm{\;m}}^{2},{J}_{2} = {25}\mathrm{\;{kg}}{\mathrm{\;m}}^{2} \) , then

\[
{\widetilde{\omega }}_{1} \approx  {98}\mathrm{{rad}}/\mathrm{s},\;\lambda  \approx   - {0.16}{\mathrm{\;s}}^{-1}.
\]

Because we are interested in \( {\omega }_{2} \) we first calculate \( {\omega }_{1} \) then \( {\omega }_{2}\left( t\right)  = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}\left( t\right) \) . Note that the initial condition must also be translated as \( {\omega }_{1}\left( 0\right)  = \left( {{r}_{2}/{r}_{1}}\right) {\omega }_{2}\left( 0\right) \) .

The responses when \( {\omega }_{2}\left( 0\right)  = 0,{\omega }_{2}\left( 0\right)  = 3\mathrm{{rad}}/\mathrm{s} \) , and \( {\omega }_{2}\left( 0\right)  = 6\mathrm{{rad}}/\mathrm{s} \) should be as in the following plot:

![bo_d5ctcr3ef24c73bj2om0_14_315_911_777_242_0.jpg](images\bo_d5ctcr3ef24c73bj2om0_14_315_911_777_242_0.jpg)

## Teaching Points
1. Mechanical systems with damping often reduce to first-order dynamics.
2. Belt constraints directly define system input–output relationships.
3. Steady-state speed depends on damping, not inertia.
4. Inertia primarily affects the transient response speed.
5. Initial conditions influence transient behavior but not steady state.
