# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Define the square matrix 
𝐴
A with given elements.
### Step 2: 
Store the elements in a NumPy array for performing matrix operations.
### Step 3: 
Use the function np.linalg.eig(A) to calculate the eigenvalues and eigenvectors of 
𝐴
A.
### Step 4: 
Print the eigenvalues and corresponding eigenvectors as output.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:KARTHIK PADMANABAN R 
#RegisterNumber:212224110029

import numpy as np

A = np.array([[2, -3, 0],
              [2, -5, 0],
              [0,  0,  3]])

values, vectors = np.linalg.eig(A)
print("Eigen values are", values, "and Eigen Vectors are", vectors)

```
## Output:
<img width="1345" height="878" alt="Screenshot 2025-09-01 105556" src="https://github.com/user-attachments/assets/7cfa0459-5301-4c8e-b78f-a5fcdd244e88" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
