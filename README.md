# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation.
### Step 2: Prepare the lists from each equations and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: RAVIPRASATH K
#RegisterNumber: 212224230225
import numpy as np
A = np.array([[2, -3, 0],[2, -5, 0], [0, 0, 3]])
values,vectors = np.linalg.eig(A)
print(f"Eigen values are {values} and Eigen Vectors are {vectors}")
```
## Output:

![image](https://github.com/user-attachments/assets/99513ec5-3fd9-4d99-a37b-ef8f7dc4eba3)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
