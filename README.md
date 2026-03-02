# MINI-PROJECT2
Linear Transformation Pipeline — NumPy
Overview

This project implements a fully vectorized linear transformation pipeline using NumPy. It follows standard machine learning preprocessing steps and avoids any use of Python loops.

Objectives

Create input matrix X (batch_size, n_features)

Create compatible weight matrix W and bias vector b

Standardize input features column-wise

Apply linear transformation using matrix multiplication

Optionally normalize output rows

Print shapes at each step for verification

Use only vectorized NumPy operations

Key Concepts

Matrix multiplication using @

Broadcasting with bias vector

Column-wise standardization

Row normalization

Shape validation for dimensional consistency

Efficient vectorized computation

Implementation Details

The pipeline first prepares the input data and parameters, then standardizes features to ensure consistent scaling. After that, it applies a linear transformation and optionally normalizes the output. Each stage prints tensor shapes to confirm compatibility and correctness.

Technologies Used

Python

NumPy

Output

The script prints matrix shapes at every stage to ensure correct dimensions throughout the transformation process.
