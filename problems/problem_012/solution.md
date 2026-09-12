# Solution

## Method 
The terminal velocity in the free-fall and the parachute phases can be calculated using

\[
\mathop{\lim }\limits_{{t \rightarrow  \infty }}v\left( t\right)  = \mathop{\lim }\limits_{{t \rightarrow  \infty }}\widetilde{v}\left( {1 - {e}^{\lambda t}}\right)  + v\left( 0\right) {e}^{-{\lambda t}} = \widetilde{v}
\]

where

\[
\lambda  =  - \frac{b}{m}
\]

\[
\widetilde{v} = \frac{mg}{b}.
\]

In this problem \( m = {70}\mathrm{\;{kg}}, g = {10}\mathrm{\;m}/{\mathrm{s}}^{2} \) , and

\[
{\widetilde{v}}_{f} = {200}\mathrm{\;{km}}/\mathrm{h} \approx  {56}\mathrm{\;m}/\mathrm{s}
\]

during free-fall and

\[
{\widetilde{v}}_{c} = {20}\mathrm{\;{km}}/\mathrm{h} \approx  {5.6}\mathrm{\;m}/\mathrm{s}
\]

after the parachute opens. From these we calculate

\[
{b}_{f} = \frac{mg}{{\widetilde{v}}_{f}} = \frac{700}{56} \approx  {12.6}\mathrm{\;{kg}}/\mathrm{s}\;{b}_{c} = \frac{mg}{{\widetilde{v}}_{c}} = \frac{700}{5.6} \approx  {126}\mathrm{\;{kg}}/\mathrm{s}
\]

with which

\[
{\lambda }_{f} =  - \frac{{b}_{f}}{m} \approx   - {0.18}{\mathrm{\;s}}^{-1}\;{\lambda }_{c} =  - \frac{{b}_{f}}{m} \approx   - {1.8}{\mathrm{\;s}}^{-1}.
\]

The time constants in each phase are

\[
{\tau }_{f} =  - {\lambda }_{f}^{-1} \approx  {5.5}\mathrm{\;s},\;{\tau }_{c} =  - {\lambda }_{c}^{-1} \approx  {0.55}\mathrm{\;s}.
\]

Assuming that the speed at free-fall is close to \( {\widetilde{v}}_{f} \) when the parachute opens we can calculate

\[
{v}_{c}\left( t\right)  = {\widetilde{v}}_{c}\left( {1 - {e}^{{\lambda }_{c}t}}\right)  + {\widetilde{v}}_{f}{e}^{-{\lambda }_{c}t}
\]

from which the time necessary to reach \( {29}\mathrm{\;{km}}/\mathrm{h} \) is

\[
{v}_{c}\left( {t}^{ * }\right)  = {\widetilde{v}}_{c}\left( {1 - {e}^{{\lambda }_{c}{t}^{ * }}}\right)  + {\widetilde{v}}_{f}{e}^{-{\lambda }_{c}{t}^{ * }} = {29}\mathrm{\;{km}}/\mathrm{h} \approx  8\mathrm{\;m}/\mathrm{s}.
\]

or

\[
{5.6} + \left( {{56} - {5.6}}\right) {e}^{-{1.8}{t}^{ * }} \approx  8\mathrm{\;m}/\mathrm{s}\; \Rightarrow  \;{t}^{ * } \approx   - \frac{1}{1.8}\log \frac{8 - {5.6}}{{56} - {5.6}} \approx  {1.7}\mathrm{\;s}
\]

so the parachute should be opened at least 1.7s prior to landing.

As for the height we calculate

\[
{h}_{c}\left( t\right)  = {h}_{c}\left( 0\right)  - {x}_{c}\left( t\right)  = {h}_{c}\left( 0\right)  - {x}_{c}\left( 0\right)  - {\widetilde{v}}_{c}t + \frac{\left( {\widetilde{v}}_{f} - {\widetilde{v}}_{c}\right) }{{\lambda }_{c}}\left( {1 - {e}^{{\lambda }_{c}t}}\right)
\]

where \( t = 0 \) is the moment the parachute opens and \( {x}_{c}\left( 0\right) \) can be considered equal to 0 . If after \( {t}^{ * } \approx  {1.7}\mathrm{\;s} \) we have landed then \( {h}_{c}\left( {t}^{ * }\right)  = 0 \) and

\[
{h}_{c}\left( 0\right)  = {5.6} \times  {1.7} + \frac{\left( {56} - {5.6}\right) }{1.8}\left( {1 - {e}^{-{1.8} \times  {1.7}}}\right)  \approx  {5.6} \times  {1.7} + {28} \times  {0.95} \approx  {36}\mathrm{\;m}
\]

is the minimum height at which the parachute can be opened.

If the dive starts at \( 4\mathrm{\;{km}} \) or \( {4000}\mathrm{\;m} \) with zero vertical velocity and the parachute is opened after \( {60}\mathrm{\;s} \) , at that point the diver should be at the heigth

\[
{h}_{f}\left( {60}\right)  = {h}_{f}\left( 0\right)  - {x}_{f}\left( 0\right)  - {\widetilde{v}}_{f} \times  {60} + \frac{\left( {v}_{f}\left( 0\right)  - {\widetilde{v}}_{f}\right) }{{\lambda }_{f}}\left( {1 - {e}^{{\lambda }_{f} \times  {60}}}\right)
\]

\[
= {4000} - 0 - {56} \times  {60} + \frac{56}{0.18}\left( {1 - {e}^{-{0.18} \times  {60}}}\right)  \approx  {975}\mathrm{\;m}
\]

From that height the fall will continue until

\[
0 = {h}_{c}\left( 0\right)  - {x}_{c}\left( 0\right)  - {\widetilde{v}}_{c}t + \frac{\left( {\widetilde{v}}_{f} - {\widetilde{v}}_{c}\right) }{{\lambda }_{c}}\left( {1 - {e}^{{\lambda }_{c}t}}\right)
\]

\[
= {975} - 0 - {5.6t} + \frac{\left( {56} - {5.6}\right) }{1.8}\left( {1 - {e}^{-{1.8} \times  t}}\right)
\]

This is approximately \( {975}/{5.6} \approx  {176}\mathrm{\;s} \) . One can solve the nonlinear equation for a more accurate solution of about 181s. The total time airborne is approximately \( {60} + {181} = {240}\mathrm{\;s} \) , that is 4 minutes.

## Teaching Points
1. Terminal velocity determines resistance coefficients.
2. Time constants characterize transient behavior.
3. Piecewise models are effective for multi-phase dynamics.
4. Engineering constraints translate into timing and distance requirements.
