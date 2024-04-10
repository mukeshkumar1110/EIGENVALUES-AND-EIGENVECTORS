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
#Developed by: Mukesh Kumar S
#RegisterNumber:212223240099

import numpy as np
A=[[-2,2,-3],[2,1,-6],[-1,-2,0]]
values,Vectors=np.linalg.eig(A)
print("Eigen values are",values,"and Eigen Vectors are",Vectors)
```
## Output:
![Screenshot 2024-04-10 193802](https://github.com/mukeshkumar1110/EIGENVALUES-AND-EIGENVECTORS/assets/152305679/d90fb4d4-2d5a-47b3-b7bd-cd14ed5e37ee)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
