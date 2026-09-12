# Solution

## Method
Calculate

\[
\frac{\Gamma \left( s\right) }{U\left( s\right) } = \frac{g}{s + f}.
\]

Because of linearity

\[
\frac{\widetilde{\Gamma }\left( s\right) }{\widetilde{U}\left( s\right) } = \frac{g}{s + f}
\]

and combine

\[
\frac{\widetilde{Y}\left( s\right) }{\widetilde{U}\left( s\right) } = \frac{\widetilde{Y}\left( s\right) }{\widetilde{\Gamma }\left( s\right) }\frac{\widetilde{\Gamma }\left( s\right) }{\widetilde{U}\left( s\right) } = \frac{-b{\bar{x}}_{2}}{\left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) } \times  \frac{g}{s + f} = \frac{-{gb}{\bar{x}}_{2}}{\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) }
\]

Substituting numerical values:

\[
\frac{\widetilde{Y}\left( s\right) }{\widetilde{U}\left( s\right) } =  = \frac{-{gb}{\bar{x}}_{2}}{\left( {s + f}\right) \left( {s + a}\right) \left( {s + c + {\bar{x}}_{1}}\right) } = \frac{-1/{53.31}/{33}^{2}}{\left( {s + 1/5}\right) \left( {s + 1/{33}}\right) \left( {s + 1/{33}}\right) } = \frac{-{3.3}}{\left( {{5s} + 1}\right) {\left( {33}s + 1\right) }^{2}}
\]

which has poles at \( - 1/{33} \) and \( - 1/5 \) and no zeros.

## Teaching Points
1. Cascading subsystems using transfer-function multiplication
2. Modeling actuator and transport dynamics explicitly
3. Effect of additional dynamics on system order
4. Identification of poles in higher-order biomedical models
5. Interpretation of time constants in physiological systems
