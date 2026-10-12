# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the NumPy library to perform matrix operations.
### Step 2: Get the matrix elements from the user and convert them into a NumPy array.
### Step 3: Use the numpy.linalg.eig() function to calculate the eigenvalues and eigenvectors of the matrix.
### Step 4: Display the eigenvalues and eigenvectors as the output.
## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as p
a=p.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
b,c=p.linalg.eig(a)
print(f"Eigen values are {b} and Eigen Vectors are {c}")
```
## Output:
<img width="1501" height="702" alt="image" src="https://github.com/user-attachments/assets/d470b658-da65-4605-9e77-3e5bcdbed83c" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
