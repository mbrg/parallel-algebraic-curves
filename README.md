# Parallel Algebraic Curves

## Intro

An [Algebraic Curve](https://en.wikipedia.org/wiki/Algebraic_curve) is the set of coordiantes which evaluate a polynomial to zero (i.e it's roots). To be more formal, a polynomial ![equation](http://latex.codecogs.com/gif.latex?F) defines an Algebraic Curve by: ![equation](http://latex.codecogs.com/gif.latex?%5C%7B%28x_1%2Cx_2%29%20%5Cin%20%5CBbb%20R%5E2%7CF%28x_1%2Cx_2%29%3D0%5C%7D).

#### How do Algebraic Curves look like, when the coordinates axes are put in parallel?

Transforming a point in Euclidean R^2 to parallel coordinates yields a 2d-line:

<img src="https://ars.els-cdn.com/content/image/1-s2.0-S095354380600052X-gr1.jpg" width="400" height="200"/>  source: ref [3]

How does a circle look like after transforming each of its points to parallel coordinates? Well, it looks like a bunch of lines. We can represent the circle by the Envelope of these lines! Which yields:

<img src="/curve_showoff/circle.png" width="800" height="400"/> 

## Code Description

Algebraic Curves translated to Parallel Coordiantes.

Creates an animated plot of an Algebraic Curve next to its dual in Parallel Coordinates, given by the *Inselberg Transformation*.

To create your own curve, run [curve_animation](curve_animation.ipynb) notebook and change the curve parameters.

## A Quick Showoff

![equation](http://latex.codecogs.com/gif.latex?F%28x_1%2Cx_2%29%20%3D%20x_1%5E2&plus;x_2%5E2-1) 

<img src="/curve_showoff/x1^2+x2^2-1.gif" alt="x1^2+x2^2-1" width="800" height="400"/> 

![equation](http://latex.codecogs.com/gif.latex?F%28x_1%2Cx_2%29%3D%20x_1%5E3%20&plus;%202x_1%5E2%20-%20x_1%20-%20x_2%5E2) 

<img src="/curve_showoff/x1^3+2 x1^2-x1-x2^2.gif" alt="x1^3+2 x1^2-x1-x2^2" width="800" height="400"/> 

![equation](http://latex.codecogs.com/gif.latex?F%28x_1%2Cx_2%29%3D%20x_1%5E3&plus;x_1%5E2-x_1-1-x_2) 

<img src="/curve_showoff/x1^3+x1^2-x1-1-x2.gif" alt="x1^3+x1^2-x1-1-x2" width="800" height="400"/> 

![equation](http://latex.codecogs.com/gif.latex?F%28x_1%2Cx_2%29%3D%20x_1%5E3-x_1-x_2%5E2) 

<img src="/curve_showoff/x1^3-x1-x2^2.gif" alt="x1^3-x1-x2^2" width="800" height="400"/> 

![equation](http://latex.codecogs.com/gif.latex?F%28x_1%2Cx_2%29%3D%20x_1%5E3&plus;x_1%5E2&plus;x_1%u2212x_2%5E2) 

<img src="/curve_showoff/x1^3+x1^2+x1−x2^2.gif" alt="x1^3+x1^2+x1−x2^2" width="800" height="400"/> 

## References

1. Inselberg A., Dimsdale B. (1987) Parallel Coordinates for Visualizing Multi-Dimensional Geometry. In: Kunii T.L. (eds) Computer Graphics 1987. Springer, Tokyo
2. B. Dimsdale. Conic Transformations and Projectivities – IBM LASC Tech. Rep. G320-2753. IBM LA Scientific Center, 1984.
3. Siirtola, H., & Räihä, K. J. (2006). Interacting with parallel coordinates. Interacting with Computers, 18(6), 1278-1309.
