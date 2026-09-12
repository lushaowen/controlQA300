# Solution

## Method

Taking Laplace transforms yields the transfer-function

\[
G\left( s\right)  = \frac{-{s}^{2}}{{s}^{2} + \frac{b}{m}s + \frac{k}{m}}.
\]

Comparing coefficients with the second order characteristic equation \( {s}^{2} + {2\zeta }{\omega }_{n}s + {\omega }_{n}^{2} \), we have

\[
k = m{\omega }_{n}^{2} = m{\left( 2\pi {f}_{n}\right) }^{2} \approx  {158} \times  {10}^{3}\frac{kg}{{s}^{2}},\;b = {2m\zeta }{\omega }_{n} = {4m\zeta \pi }{f}_{n} \approx  {1.61} \times  {10}^{3}\frac{kg}{s}.
\]

The corresponding roots are

\[
\lambda  =  - {\omega }_{n}\left( {\zeta  \pm  \sqrt{{\zeta }^{2} - 1}}\right)  \approx   - {1.26} \pm  {15.66j}.
\]

## Teaching Points

1. Modeling vehicle suspension systems using lumped parameters
2. Base excitation and relative displacement formulation
3. Relationship between physical parameters and modal properties
4. Interpretation of natural frequency and damping ratio
5. Physical meaning of pole locations in ride comfort analysis
