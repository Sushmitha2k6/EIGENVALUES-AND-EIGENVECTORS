NAME:SUSHMITHA S

REG NO:212224230282


# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
Import the numpy module to use the built-in functions for calculation

Step 2:
Prepare the lists from the matrix and assign in np.array()

Step 3:
Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

Step 4:
End the program.

## Program:

#Program to find the eigen values and eigen vectors.
#Developed by: SUSHMITHA S
#Register Number: 212224230282
 
import numpy as np
A=np.array([[4,2],[2,4]])
values,Vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,Vectors))

## Output:


![image](https://github.com/user-attachments/assets/cb4e8164-f81d-4edf-898e-fb61eb655597)


## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
