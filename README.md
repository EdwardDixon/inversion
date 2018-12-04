# Inversion

Section 9.1.7 of the famous [Grammar of Graphics](https://www.amazon.com/Grammar-Graphics-Statistics-Computing/dp/0387245448) 
by [Leland Wilkinson](https://en.wikipedia.org/wiki/Leland_Wilkinson) describes how to use 'Complex inversion' to turn the plane inside out.

In polar coordinates, the transform looks like this:

![Inversion in polar coordinates](inversion_in_polar_coordinates.gif)

The complex conjugate of ![z](z.gif) is given by ![complex conjugate of z](complex_conjugate_of_z.gif).  We use the complex conjugate to transform the complex plane
like this:  

![inversion using complex conjugate](inversion_complex_conjugate.gif)

This can be a neat trick to expose detail hidden near the centre of a polar plot - or we can just use it to mangle photos beyond all recognition!

![Face before and after inversion](abbeylee_before_and_after.png)

[Code in the notebook](Complex Inversion.ipynb). Have fun!
