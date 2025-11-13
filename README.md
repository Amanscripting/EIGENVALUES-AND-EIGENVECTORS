# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy library to access its linear algebra functions
### Step 2: Define or input the square matrix (2D NumPy array) for which eigenvalues and eigenvectors need to be found
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: Store and print (or further process) the eigenvalues and eigenvectors as needed.​
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Aman Alam
#RegisterNumber:212224240011
import numpy as np
matrix=np.array([[2,2],[1,3]])
eigen_values,eigen_vector=np.linalg.eig(matrix)
print("Eigen values are {} and Eigen Vectors are {}".format(eigen_values,eigen_vector))
```

## Output:
<img width="1217" height="111" alt="Screenshot 2025-10-23 104556" src="https://github.com/user-attachments/assets/e0201afc-7392-4927-8139-5deaa6b4034a" />

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
