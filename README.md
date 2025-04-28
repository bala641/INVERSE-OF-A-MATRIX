# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
 
### Step1 : Input the Matrix:
Start with a square matrix A (number of rows = number of columns).

### Step 2: Check if Invertible:

Compute the determinant of A (det(A)).

If det(A) = 0, the matrix is singular and does not have an inverse.

Otherwise, proceed.

### Step 3: Apply Inverse Formula (Mathematically):

Adjugate Method:
Inverse of A = (1 / det(A)) × adj(A)
Where adj(A) = transpose of the cofactor matrix of A.

### Step 4: Use Computational Tool:

Use numpy.linalg.inv(A) to directly compute the inverse using efficient algorithms (like LU decomposition internally).

### Step 5: Output the Inverse Matrix:
Display or return the inverse matrix.
## Program:

#Program to find the inverse of a matrix.
#Developed by: BALA B
#RegisterNumber:212224100005
~~~python
import numpy as np
a=np.array([[6,2,3],[3,1,1],[10,3,4]])
b=np.linalg.inv(a)
print(b)
~~~


## Output:

![image](https://github.com/user-attachments/assets/df08acd1-b06d-4210-9016-8cc45e6eb2dd)

## Result:
Thus the inverse of given matrix is successfully solved using python program

