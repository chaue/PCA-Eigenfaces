# PCAEigenfaces
A translation of Prof. Haddock's MATLAB code that performs PCA dimension reduction to compress facial images

There are a few things of note when going from MATLAB to Python 
- flattening a matrix into a vector in Python to achieve the same result as MATLAB requires the argument order="F", as MATLAB flattens by column rather than row
- When subtracting unsigned values in MATLAB, negative results implicitly convert to 0. However, in Python would be negative values wrap around and return a very large number
