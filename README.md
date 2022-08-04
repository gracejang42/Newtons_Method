# Newtons_Method
Root-finding algorithm implementation in python 

The Newton-Raphson Method is a root-finding algorithm which produces successively better approximations to the roots (or zeros) or a real-valued function. The basic version of this method can be written as,

x1 = x0 - f(x0)/f’(x0)   where,

f is a single-variable function defined for a real variable x 
f’ is the derivative of f 
x0 is an initial guess for the root of f 
x1 is a better approximation of the root than x0

Geometrically, (x1, 0) is the intersection of the x-axis and the tangent of the graph of f at (x0, f(x0)), meaning the improved guess is the unique root of the linear approximation at the initial point. The process is repeated as,

x_n+1 = x_n - f(x_n)/f’(xn) 

until a sufficiently precise value is reached. 
