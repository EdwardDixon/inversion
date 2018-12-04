# Inversion

Section 9.1.7 of the famous [Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448) 
by [Leland Wilkinson](https://en.wikipedia.org/wiki/Leland_Wilkinson) describes how to use 'Complex inversion' to turn the plane inside out.

In polar coordinates, the transform looks like this:

\[ (\Rho,\Theta) \to (1/\Rho, \Theta) \]

The complex conjugate of \[ z = z + iy \]  is given by \[ z\bar = x - iy \].  We use the complex conjugate to transform the complex plane
like this:  \[ z \to 1 / z\bar \]
