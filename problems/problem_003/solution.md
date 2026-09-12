# Solution

## Method

Possible MATLAB code for plotting and analyzing the data:

% Landing distances (d)

D_134 = [13+15/16, 19+13/16, 27+11/16, 33+3/8 ;  
    13+7/8 , 19+13/16, 27+3/4 , 33+5/16;  
    14+1/16 , 19+13/16, 27+3/4 , 33+3/16;  
    14    , 19+3/4 , 27+9/16 , 33+7/16;  
    13+15/16, 19+3/4 , 27+9/16 , 33+5/8 ];

---

D_67 = [10+11/16 , 14+1/2 , 20+3/4 , 25+7/16, 29+5/8 ;  
    10+11/16 , 14+9/16 , 20+3/4 , 25+1/2 , 29+1/2 ;  
    10+11/16 , 14+1/2 , 20+3/4 , 25+3/4 , 29+1/2 ;  
    10+11/16 , 14+1/2 , 20+3/4 , 25+1/2 , 29+5/16;  
    10+11/16 , 14+9/16 , 20+3/16 , 25+5/8 , 29+1/2 ];


% Reshape arrays

d_134 = reshape(D_134, size(D_134, 1)*size(D_134, 2), 1);

d_67 = reshape(D_67, size(D_67,1)*size(D_67,2),1);

% Inclined plane distance (1)

e = ones(5,1);

1_134 = [1*e; 2*e; 4*e; 6*e];

1_67 = [1*e; 2*e; 4*e; 6*e; 8*e];

% Convert to heigth in inches

h_134 = 12*1_134*sin(13.4/180*pi);

h_67 = 12*1_67*sin(6.7/180*pi);

% Stack data

d_data = [d_134 ; d_67] ;

h_data = [h_134 ; h_67];

% Fit linear curve

f1 = fit(d_data, h_data, fittype('a*x'));

% Fit quadratic curve

f2 = fit(d_data, h_data, fittype('a*x^2'));

dvec = linspace \( \left( {0,{40},{100}}\right) \) ;

h1vec = f1.a * dvec;

h2vec = f2.a * dvec.^2;

% Plot data and fit

plot(dvec, h1vec, '-r', dvec, h2vec, '-b', d_data, h_data, 'kx')

ylabel('h in inches')

xlabel('d in inches')

grid on

---

![bo_d5ctcr3ef24c73bj2om0_7_467_1605_785_270_0.jpg](images\bo_d5ctcr3ef24c73bj2om0_7_467_1605_785_270_0.jpg)

A quadratic fit seems to approximates the experimental data well within the given range and confirms the behavior one would expect from physics.

\[
{mgh} = \frac{1}{2}m{v}^{2}.
\]

While the projectile accelerates down the ramp, potential energy is converted to kinetic energy as in

In other words the horizontal velocity leaving the ramp should be close to

\[
v = \sqrt{2gh}
\]

and it remains approximately constant as long as it is falling.

If we assume that at the time the projectile leaves the ramp it has no vertical velocity then the vertical distance travelled is

\[
y = \frac{1}{2}g{t}^{2}
\]

where \( t \) is the time it takes to hit the ground. Because the distance \( y \) is kept constant is should take approximately the same time to fall in all trials.

The distance travelled \( d \) should therefore be

\[
d = {vt} = \sqrt{2gh}\sqrt{{2y}/g}
\]

or

\[
h = \frac{1}{4y}{d}^{2}
\]

The coefficient obtained experimentally therefore tells you how high the apparatus was set. You should get about 18in as an answer.


## Teaching Points
1. Relationship between experimental data and physical laws
2. Use of curve fitting to validate theoretical models
3. Interpretation of quadratic behavior in projectile motion
4. Importance of unit consistency in numerical modeling
5. Estimation of physical parameters from experimental data

