# e-logistic-regression-and-neural-networks-to-recognize-handwritten-digits-from-0-to-9-.-Multi-class
**MultiClassClasification**

You are given a data set in ex3data1.mat that contains 5000 training examples of handwritten digits.2 The .mat format means that that the data has
been saved in a native Octave/MATLAB matrix format, instead of a text
(ASCII) format like a csv-file. These matrices can be read directly into your
program by using the load command. After loading, matrices of the correct
dimensions and values will appear in your program’s memory. The matrix
will already be named, so you do not need to assign names to them.

There are 5000 training examples in ex3data1.mat, where each training
example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is
represented by a floating point number indicating the grayscale intensity at
that location. The 20 by 20 grid of pixels is “unrolled” into a 400-dimensional
vector. Each of these training examples becomes a single row in our data
matrix X. This gives us a 5000 by 400 matrix X where every row is a training
example for a handwritten digit image.
