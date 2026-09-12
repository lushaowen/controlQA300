# Solution



## Method

Because

\[
\alpha  = \frac{1}{J}\left( {b + \frac{{K}_{t}{K}_{e}}{{R}_{a}}}\right) ,\;{\alpha }^{\prime } = \frac{1}{J + {J}^{\prime }}\left( {b + \frac{{K}_{t}{K}_{e}}{{R}_{a}}}\right) ,
\]

\[
\frac{J + {J}^{\prime }}{J} = \frac{1 + \frac{J}{{J}^{\prime }}}{\frac{J}{{J}^{\prime }}} = \frac{\alpha }{{\alpha }^{\prime }}
\]

we calculate with \( {J}^{\prime } = {0.001}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}\alpha  = 1/{0.1} = {10}{\mathrm{\;s}}^{-1} \) and \( {\alpha }^{\prime } = 1/{0.54} \approx  {1.86}{\mathrm{\;s}}^{-1} \)

\[
J = \frac{{J}^{\prime }}{\frac{\alpha }{{\alpha }^{\prime }} - 1} = \frac{{J}^{\prime }{\alpha }^{\prime }}{\alpha  - {\alpha }^{\prime }} \approx  {227.2} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}
\]

After determining \( J \) we can calculate

\[
{K}_{t} = \frac{{\alpha J}{R}_{a}\widetilde{\omega }}{{\bar{v}}_{a}} = \frac{{10} \times  {227.2} \times  {10}^{-6} \times  {0.2} \times  {2\pi 5000}}{{60} \times  {12}} \approx  {0.02}\frac{\mathrm{{Nm}}}{\mathrm{A}}
\]

and \( {K}_{e} = {K}_{t} = {0.02}\mathrm{\;V}\mathrm{\;s}/\mathrm{{rad}} \) . The last unknown quantity is

\[
b = {\alpha J} - \frac{{K}_{t}{K}_{e}}{{R}_{a}} = {10} \times  {227.2} \times  {10}^{-6} - \frac{{0.02}^{2}}{0.2} \approx  {289.4} \times  {10}^{-6}\mathrm{\;{kg}}{\mathrm{\;m}}^{2}/\mathrm{s}.
\]

## Teaching Points

1. Adding inertia provides a safe alternative to stall testing.
2. Motor time constants directly reflect inertia and damping.
3. Comparing system poles before and after modification enables parameter identification.
4. Torque and back-emf constants remain equal in SI units.
5. This method is especially useful for motors with gearboxes.
