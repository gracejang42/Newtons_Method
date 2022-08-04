# Newtons_Method
**Root-finding algorithm implementation in python** 

The Newton-Raphson Method is a root-finding algorithm which produces successively better approximations to the roots (or zeros) or a real-valued function. The basic version of this method can be written as,

$x_1 = x_0-\frac{f \left(x_0\right)}{f^{'}\left(x_0\right)}$   
where,
```
f is a single-variable function defined for a real variable x 
f’ is the derivative of f 
x0 is an initial guess for the root of f 
x1 is a better approximation of the root than x0
```
Geometrically, $\left(x_1, 0\right)$ is the intersection of the x-axis and the tangent of the graph of *f* at $\left(x_0, f\left(x_0\right)\right)$, meaning the improved guess is the unique root of the linear approximation at the initial point. The process is repeated as,

$x_{n+1}=x_n - \frac{f\left(x_n\right)}{f^{'}\left(x_n \right)}$ 

until a sufficiently precise value is reached. 

-----------------------------------------------------

There are two examples provided in this repository, both of which use a similar python approach to using Newton’s Method for approximating solutions. 

NewtonFinal solves,

1/(1 + e^x - 1/2)


otherNewton solves,

sin(x^2) - x^3 -1 

