# Solution

## Method
The terminal velocity in the free-fall and the parachute phases can be calculated using

\[
\mathop{\lim }\limits_{{t \rightarrow  \infty }}v\left( t\right)  = \mathop{\lim }\limits_{{t \rightarrow  \infty }}\frac{1 + \alpha {e}^{\lambda t}}{1 - \alpha {e}^{\lambda t}}\widetilde{v} = \widetilde{v}.
\]

As in \( \mathrm{P}{2.8}, m = {70}\mathrm{\;{kg}}, g = {10}\mathrm{\;m}/{\mathrm{s}}^{2} \) , and

\[
{\widetilde{v}}_{f} = {200}\mathrm{\;{km}}/\mathrm{h} \approx  {56}\mathrm{\;m}/\mathrm{s}
\]

during free-fall and

\[
{\widetilde{v}}_{c} = {20}\mathrm{\;{km}}/\mathrm{h} \approx  {5.6}\mathrm{\;m}/\mathrm{s}
\]

after the parachute opens. From these we calculate

\[
{b}_{f} = \frac{mg}{{\widetilde{v}}_{f}^{2}} = \frac{700}{{56}^{2}} \approx  {0.227}\mathrm{\;{kg}}/{\mathrm{s}}^{2}\;{b}_{c} = \frac{mg}{{\widetilde{v}}_{c}^{2}} = \frac{700}{{5.6}^{2}} \approx  {22.7}\mathrm{\;{kg}}/{\mathrm{s}}^{2}
\]

with which

\[
{\lambda }_{f} =  - \frac{{b}_{f}}{m} \approx   - {0.36}\;{\lambda }_{c} =  - \frac{{b}_{f}}{m} \approx   - {3.6}.
\]

Because the system is now nonlinear we have to calculate the time constants based on the definition, that is \( \tau \) is the time at which, starting from \( v\left( 0\right)  = 0 \) ,

\[
v\left( t\right)  = \left( {1 - {e}^{-1}}\right) \widetilde{v}
\]

that is

\[
\frac{1 + \alpha {e}^{\lambda t}}{1 - \alpha {e}^{\lambda t}} = 1 - {e}^{-1},\;\alpha  = \frac{v\left( 0\right)  - \widetilde{v}}{v\left( 0\right)  + \widetilde{v}} =  - 1,
\]

which implies

\[
\tau  =  - {\lambda }^{-1}\ln \left( {{2e} - 1}\right) .
\]

Using this formula the time constants in each phase are

\[
{\tau }_{f} =  - {\lambda }_{f}^{-1} \approx  {4.1}\mathrm{\;s},\;{\tau }_{c} =  - {\lambda }_{c}^{-1} \approx  {0.41}\mathrm{\;s}.
\]

Assuming that the speed at free-fall is close to \( {\widetilde{v}}_{f} \) when the parachute opens we can calculate

\[
{v}_{c}\left( t\right)  = \frac{1 + \alpha {e}^{{\lambda }_{c}t}}{1 - \alpha {e}^{{\lambda }_{c}t}}\widetilde{v},\;\alpha  = \frac{{\widetilde{v}}_{f} - {\widetilde{v}}_{c}}{{\widetilde{v}}_{f} + {\widetilde{v}}_{c}} \approx  {0.82}
\]

from which the time necessary to reach \( v\left( {t}^{ * }\right)  = {29}\mathrm{\;{km}}/\mathrm{h} \) is

\[
{t}^{ * } = {\lambda }_{c}^{-1}\ln \left( \frac{{v}_{c}\left( {t}^{ * }\right)  - {\widetilde{v}}_{c}}{\left( {{v}_{c}\left( {t}^{ * }\right)  + {\widetilde{v}}_{c}}\right) \alpha }\right)  \approx  {0.42}\mathrm{\;s},
\]

so the parachute should be opened at least \( {0.42}\mathrm{\;s} \) prior to landing.

In order to calculate the height we first integrate

\[
{x}_{c}\left( t\right)  = {x}_{c}\left( 0\right)  + {\int }_{0}^{t}{v}_{c}\left( \tau \right) {d\tau } = {x}_{c}\left( 0\right)  + {\widetilde{v}}_{c}t + \frac{2{\widetilde{v}}_{c}}{{\lambda }_{c}}\ln \left( \frac{1 - \alpha }{1 - \alpha {e}^{{\lambda }_{c}t}}\right)
\]

then calculate for \( t = {t}^{ * },{h}_{c}\left( {t}^{ * }\right)  = 0 \) , and \( {x}_{c}\left( 0\right)  = 0 \) , the quantity

\[
{h}_{c}\left( 0\right)  = {h}_{c}\left( {t}^{ * }\right)  + {x}_{c}\left( {t}^{ * }\right)  = {x}_{c}\left( {t}^{ * }\right)  \approx  {6.9}\mathrm{\;m},
\]

which is the minimum height at which the parachute can be opened.

If the dive starts at \( 4\mathrm{\;{km}} \) or \( {h}_{f}\left( 0\right)  = {4000}\mathrm{\;m} \) with zero vertical velocity and the parachute is opened after 60s, at that point the diver should be at the heigth

\[
{h}_{f}\left( {60}\right)  = {h}_{f}\left( 0\right)  - {x}_{f}\left( 0\right)  - {\widetilde{v}}_{f}{60} + \frac{2{\widetilde{v}}_{f}}{{\lambda }_{f}}\ln \left( \frac{1 - \alpha }{1 - \alpha {e}^{{\lambda }_{f}{60}}}\right)  \approx  {880}\mathrm{\;m}
\]

From that height the fall will continue until

\[
0 = {h}_{c}\left( t\right)  = {h}_{c}\left( 0\right)  - {x}_{c}\left( t\right)
\]

\[
= {880} - 0 - {\widetilde{v}}_{c}t + \frac{2{\widetilde{v}}_{c}}{{\lambda }_{c}}\ln \left( \frac{1 - \alpha }{1 - \alpha {e}^{{\lambda }_{c}{60}}}\right)
\]

This is approximately \( {880}/{5.6} \approx  {159}\mathrm{\;s} \) . One can solve the nonlinear equation for a more accurate solution of about \( {58}\mathrm{\;s} \) . The total time airborne is approximately \( {60} + {158} = {228}\mathrm{\;s} \) , that is a bit less than 4 minutes.

---

## Teaching Points
1. Nonlinear drag significantly alters transient behavior.
2. Time constants must be **definition-based**, not eigenvalue-based.
3. Terminal velocity dominates long-term behavior.
4. Parachute deployment timing is critical for safety.
