# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Start the program.
### Step 2: Input a square matrix.
### Step 3: Compute eigenvalues and eigenvectors using a mathematical method (e.g., NumPy linalg.eig()).
### Step 4: Display the eigenvalues and eigenvectors, then stop the program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: POPURI SAHITHYA
#RegisterNumber: 212225240106
import os 
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
a=np.array([[4,2],[2,4]])
i,e=np.linalg.eig(a)
print(f"Eigen values are {i} and Eigen Vectors are {e}")
```
## Output:
![alt text](<Screenshot 2026-05-01 195241.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
