# Finding Root Methods

This project implements several numerical methods to find the roots of functions. It includes classic algorithms like the **Bisection Method**, **Fixed Point Method**, and **Newton's Method**, as well as tools for analyzing and visualizing the root-finding process.

## Methods Included

- **Bisection Method**: A root-finding method that repeatedly bisects an interval and then selects a subinterval in which a root must lie.
- **Fixed Point Method**: A method for finding a fixed point of a function, which can be used to find the root of the function.
- **Newton's Method**: An iterative method for finding successively better approximations to the roots of a real-valued function.
- **Cubic Spline**: Interpolates data using piecewise cubic polynomials (useful for root finding in smooth functions).
- **Polynomial Solver**: Implements methods for solving polynomial equations.

## Project Structure

### **Python Scripts**
- **BisectionMethod.py**: Implements the Bisection Method for finding roots.
- **FixedPointMethod.py**: Implements the Fixed Point Method for root finding.
- **NewtonMethod.py**: Implements the Newton-Raphson method.
- **CubicSpline.py**: Implements cubic spline interpolation.
- **Polynomial.py**: Functions for solving polynomials.

### **Data Files**
- **Divided_Difference_Table.txt**: Stores the divided difference table used in Newton's method.
- **FixedPointData.txt**, **NewtonData.txt**: Test data used in Fixed Point and Newton's methods.

### **Other Files**
- **.idea**: Project-specific IDE configurations (e.g., for PyCharm).

## Requirements

- Python 3.x
- Required libraries:
  - **sympy**: For symbolic mathematics.
  - **matplotlib**: For plotting results.
  - **numpy**: For numerical operations.
