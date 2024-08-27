# Basis_Functions
Calculating the basis function for step functions (Cubic Splines, polynomials, ...etc)

The script has been implemented in R language to calculate the basis functions of the cubic Splines, polynomials when used in step functions for regressions.
It is indeed a self implementation of the function bs in the library Splines in R.

The values needed to be supplied to the function are:
- x: a vector on which the function is going to be applied
- Knots: where are the knots and thos should be located between min(x) till max(x)
- Degree: choose the degree of the polynomial where 3 is presenting a cubic spline

The results is a matrix containing the basis functions which can be used in regressions to get more flexible regressions as long as the degree is going up.

Best regards,
Mustafa Anjrini
