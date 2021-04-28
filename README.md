# SimpleRayTracer-vs0.2 package for Mathematica

The SimpleRayTracer package now incorporates:
- radiative transfer in simple disk models (either generated from [Gold et.Al Astrophys.J. 897 (2020) 2, 148](https://doi.org/10.3847/1538-4357/ab96c6) or specified by the user) to obtain intensity images,
- basic functionality for bisection of n-th images of accretion disks (light rings),
- the use of horizon-penetrating (ingoing Kerr) coordinates as an alternative to Boyer-Lindquist coordinates.

Several minor internal updates on ray tracing and bisection have been included.

# SimpleRayTracer-vs0.1 package for Mathematica

The SimpleRayTracer package for Mathematica allows to numerically ray trace light rays and obtain the shadow boundary of specified spacetimes by bisection. The only input required from the user is an analytical metric and its connection (Christoffel symbols).

The Mathematica-based package is far from optimized but rather aims at being user-friendly, easy to use, and modify to suitable need.

# Installation

To install the package simply place the full SimpleRayTracer folder into your .Mathematica/Applications folder.

# Dependencies

The current version has been tested on Mathematica 12 and has no further dependencies.

# How to use
Example files explain the usage of the package.
Once the package is loaded, the usual ?Function command in Mathematica packages gives information on how to use a function.

# Contact
If you have any questions on this project, please contact Aaron Held (a.held@imperial.ac.uk or held.aaron@gmail.com)
