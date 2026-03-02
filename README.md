# MINI-PROJECT2
Linear Transformation Pipeline — NumPy

This project implements a complete linear transformation pipeline using pure NumPy, following full vectorization (no Python loops).

Objectives

The notebook performs the following steps:

Create input matrix X (batch_size, n_features)

Create weight matrix W and bias vector b with compatible shapes

Standardize X column-wise

Compute linear transformation using matrix multiplication and bias addition

Normalize rows of Y to unit norm (optional)

Print shapes at every step

No Python loops used

Key Concepts Demonstrated

Matrix multiplication using @

Broadcasting with bias vector b

Feature standardization using:

mean(axis=0, keepdims=True)

std(axis=0, keepdims=True)

Row normalization using np.linalg.norm

Shape verification for dimensional consistency

Why No Loops?

Vectorized NumPy operations are:

Faster

More memory efficient

Closer to mathematical notation

Standard practice in machine learning pipelines

Technologies Used

Python

NumPy

Output

The script prints the shapes of:

X

W

b

means

stds

X_standardized

Y

Y_normalized

This ensures dimensional compatibility across the transformation pipeline.
