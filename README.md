# Mandelbrot set

![alt text](https://github.com/muse254/mandelbrot/blob/master/mandel.png)

--learnt from O'reilly Programming Rust;

The Mandelbrot set is defined as the set of complex numbers c for which z
does not fly out to infinity. Some go as far as to call it 'the thumb pint of God'.

However, if c is greater than 0.25, or less than –
2.0, then z eventually becomes infinitely large; otherwise, it stays
somewhere in the neighborhood of zero.

Since a complex number c has both real and imaginary components c.re
and c.im, we’ll treat these as the x and y coordinates of a point on the
Cartesian plane, and color the point black if c is in the Mandelbrot set, or
a lighter color otherwise. So for each pixel in our image, we must run the
preceding loop on the corresponding point on the complex plane, see
whether it escapes to infinity or orbits around the origin forever, and color
it accordingly.


Squaring any number smaller than 0 makes it smaller so it approaches 0

Squaring 1 yields 1

Squaring any number larger than 1 makes it larger so it approaches infinity

Squaring a positive number makes it positive
