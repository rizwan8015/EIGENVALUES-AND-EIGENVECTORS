# EIGENVALUES-AND-EIGENVECTORS
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
~~~
# Program to find the eigenvalues and eigenvectors.
# Developed by: rizwan.b
# Register Number: 24900277

import numpy as np

def compute_eigenvalues_and_vectors(matrix):
    eigenvalues, eigenvectors = np.linalg.eig(matrix)
    return eigenvalues, eigenvectors
matrix = np.array([[-2, 2, -3],
                   [2, 1, -6],
                   [-1, -2, 0]])
eigenvalues, eigenvectors = compute_eigenvalues_and_vectors(matrix)
print("Eigen values are", eigenvalues,"and Eigen Vectors are",eigenvectors)


~~~

## Output:
![Screenshot 2024-12-13 102410](https://github.com/user-attachments/assets/010dfe9c-4434-4af0-8001-dd6f2fa67834)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
