# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import NumPy library, np.linalg is its linear algebra module, which provides the eig() function to compute eigenvalues and eigenvectors.
### Step 2: Create a square matrix, Eigenvalues and eigenvectors can only be found for square matrices (same number of rows and columns).
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Print the result, This line displays the eigenvalues and eigenvectors.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: A.Ajayprabu
#RegisterNumber:212225220005

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a= np.array([[2,2],[1,3]])
values,vectors=np.linalg.eig(a)
print('Eigen values are {} and Eigen Vectors are {} '.format(values,vectors))
```

## Output:
<img width="1309" height="291" alt="image" src="https://github.com/user-attachments/assets/f5a15863-8cbd-42b3-b1ef-8296fc86dea4" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
