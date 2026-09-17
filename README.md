# EIGENVALUES-AND-EIGENVECTORS
Name : Nather Nabeel S A C

Register Number : 212224100040

## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Nather Nabeel S A C
#RegisterNumber: 212224100040

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([[2, 2],[1, 3]])

values, vectors = np.linalg.eig(A)

print(f"Eigen values are {values} and Eigen Vectors are {vectors}")

```
## Output:

<img width="1312" height="872" alt="image" src="https://github.com/user-attachments/assets/3259f522-67cc-4bce-8af4-2973109c8fa1" />


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
