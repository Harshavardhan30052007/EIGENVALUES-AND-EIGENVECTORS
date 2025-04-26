# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library
Enables functions to compute eigenvalues and eigenvectors.
### Step 2: Define the matrix
Use np.array() to create the 3x3 matrix.
### Step 3: Calculate eigenvalues and eigenvectors
Use np.linalg.eig() function to compute them.
### Step 4: Print the results
Display the eigenvalues and eigenvectors.



## Program:
```
import numpy as np
a=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values, vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {} ".format(values, vectors))
```

## Output:
![Screenshot 2025-04-26 112953](https://github.com/user-attachments/assets/f903993c-d8a0-4307-aa48-b39bb933e733)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
