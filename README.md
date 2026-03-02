# MINI-PROJECT2
🚀 Linear Transformation Pipeline — NumPy
📌 Overview

This project demonstrates a fully vectorized linear transformation pipeline built using pure NumPy.
The implementation follows best practices in numerical computing and avoids Python loops entirely.

🎯 Objectives

Create input matrix X (batch_size, n_features)

Create compatible weight matrix W and bias vector b

Standardize input features column-wise

Apply linear transformation using matrix multiplication

Optionally normalize output rows

Print shapes at each stage for verification

Use only vectorized NumPy operations

🧠 Key Concepts Demonstrated

Matrix multiplication using @

Broadcasting with bias vector

Column-wise feature standardization

Row normalization

Shape validation for dimensional consistency

Efficient vectorized computation

⚙️ Implementation Flow

Initialize input matrix and parameters

Standardize features to ensure consistent scaling

Apply linear transformation

Normalize output rows (optional)

Verify shapes at each step

🛠 Technologies Used

Python

NumPy

✅ Output

The script prints the shape of matrices throughout the pipeline to confirm correct dimensional transformations and compatibility.
