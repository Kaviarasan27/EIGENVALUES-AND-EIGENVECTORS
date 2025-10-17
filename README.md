# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy moduke to use the build-in functions for calculations

### Step 2:
Prepare the list for each linear equation and assign in np.array()

### Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
End the program

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:KAVIARASAN S B 
#RegisterNumber: 212224110030
import numpy as np

matrix = np.array([[4, 2],
                   [2, 4]])

eigenvalues, eigenvectors = np.linalg.eig(matrix)
print("Eigen values are", eigenvalues, "and Eigen Vectors are", eigenvectors)
```
## Output:

<img width="1313" height="1000" alt="image" src="https://github.com/user-attachments/assets/3d19928b-fdb8-419a-8902-50c74a4e1ada" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
