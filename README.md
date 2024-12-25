# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: The first step is to define the matrix A which is the 3x3 matrix in the program . the matrix is represented as numpy array in python, that is ,A= np.array ([[5,-3,-10],[2,2,-3],[-3,-1,5]])..
### Step 2: calculate the rank using numpy function .Use numpy's built in function np.linalg.matrix_rank(A) to compute the rank of matrix (A).The matrix_rank() function uses Singular Value Decomposition (SVD) or other methods to determine the rank of the matrix, which is the number of linearly independent rows or columns in the matrix.
### Step 3:  store the result : The result of np.linalg.matrix_rank(A) is stored in the variable solution. This represents the rank of the matrix, i.e., the number of independent rows or columns.
### Step 4: Finally, print the rank value using the print(solution) command to display the rank of the matrix on the console.
## Program:
```
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(A)
print(solution)
```
## Output:
![Screenshot (12)](https://github.com/user-attachments/assets/10868c22-37d5-4a9a-8c0f-0986e65eff32)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

