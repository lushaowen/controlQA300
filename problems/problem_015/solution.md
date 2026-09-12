# Solution

## Method

 At the inertia \( {J}_{1} \)

\[
{J}_{1}{\dot{\omega }}_{1} + {b}_{1}{\omega }_{1} = \tau  + {f}_{1}{r}_{1} - {f}_{2}{r}_{1},
\]

and at the inertia \( {J}_{2} \)

\[
{J}_{2}{\dot{\omega }}_{2} + {b}_{2}{\omega }_{2} = {f}_{2}{r}_{2} - {f}_{1}{r}_{2}.
\]

Since the inertias are coupled by a belt, the linear speeds must be the same, that is

\[
{\omega }_{1}{r}_{1} = {\omega }_{2}{r}_{2} \Rightarrow  {\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1}.
\]

Multiplying the first equation by \( {r}_{2} \) and the second by \( {r}_{1} \) we obtain

\[
{r}_{2}{J}_{1}{\dot{\omega }}_{1} + {r}_{2}{b}_{1}{\omega }_{1} = {r}_{2}\tau  + {f}_{1}{r}_{1}{r}_{2} - {f}_{2}{r}_{1}{r}_{2},
\]

\[
{r}_{1}{J}_{2}{\dot{\omega }}_{2} + {r}_{1}{b}_{2}{\omega }_{2} = {f}_{2}{r}_{1}{r}_{2} - {f}_{1}{r}_{1}{r}_{2}.
\]

Adding these together:

\[
{r}_{2}{J}_{1}{\dot{\omega }}_{1} + {r}_{1}{J}_{2}{\dot{\omega }}_{2} + {r}_{2}{b}_{1}{\omega }_{1} + {r}_{1}{b}_{2}{\omega }_{2} = {r}_{2}\tau .
\]

Substituting \( {\omega }_{2} = \left( {{r}_{1}/{r}_{2}}\right) {\omega }_{1} \) ,

\[
{r}_{2}{J}_{1}{\dot{\omega }}_{1} + {r}_{1}^{2}/{r}_{2}{J}_{2}{\dot{\omega }}_{1} + {r}_{2}{b}_{1}{\omega }_{1} + {r}_{1}^{2}/{r}_{2}{b}_{2}{\omega }_{1} = {r}_{2}\tau ,
\]

and multiplying by \( {r}_{2} \)

\[
\left( {{J}_{1}{r}_{2}^{2} + {J}_{2}{r}_{1}^{2}}\right) {\dot{\omega }}_{1} + \left( {{b}_{1}{r}_{2}^{2} + {b}_{2}{r}_{1}^{2}}\right) {\omega }_{1} = {r}_{2}^{2}\tau .
\]


## Teaching Points
1. Viscous friction introduces damping terms proportional to angular velocity.
2. Belt constraints reduce multi-inertia systems to a single dynamic equation.
3. Internal forces can be eliminated by proper equation scaling and summation.
4. Equivalent inertia and damping depend on pulley radii.
5. The result is a first-order linear differential equation suitable for control analysis.
