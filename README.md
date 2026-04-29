# euler_calc
Code to estimate a pole of rotation from GNSS / GPS data

by Eric Lindsey, last updated 2022

euler_calc.py contains a set of routines to predict plate motion velocities given an Euler pole (pole of rotation on a spherical planet). 
Routines are also provided to estimate the best-fitting euler poles from input velocity observations (e.g. GNSS velocities), and to 
identify sites moving together as one block. 

For usage and an example workflow, see the ipython notebook included.

Please cite as the following if you use this code: 

Lindsey, E. O. (2025). ericlindsey/euler_calc: October 11, 2025 Release (Version 1.0) \[Software\]. Zenodo. 

[![DOI](https://zenodo.org/badge/492018672.svg)](https://doi.org/10.5281/zenodo.17328912)


# Fengnian Chang

Modified for Tianshan and Pamir area

Supports custom polygon areas

plot observations, model predictions, and residuals map within the AOI
