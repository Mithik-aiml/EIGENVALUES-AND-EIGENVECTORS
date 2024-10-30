# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
    Import numpy as np
### Step 2: 
    Initialize the matrix using np.array()
### Step 3:
    Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
    Print the output.
## Program:

```
#Program to find the eigen values and eigen vectors.
#Developed by:Mithik jain.G 
#RegisterNumber:24001881
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
result1,result2=np.linalg.eig(A)
print(f"Eigen values are {result1} and Eigen Vectors are {result2}")

```

## Output:
![alt text](../output.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
