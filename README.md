# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
End the Program.

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Muthu Kumaran M
#RegisterNumber:23006606
import numpy as np
a=np.array([[2,2],[1,3]])
values,vectors = np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:
![Exp 4](https://github.com/Muthu-Kumaran-M/EIGENVALUES-AND-EIGENVECTORS/assets/144979439/1e4d02ed-4661-41e7-944b-f9dabdcf3de5)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
