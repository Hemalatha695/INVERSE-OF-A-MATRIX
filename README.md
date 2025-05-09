# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Use import numpy as np to access NumPy’s linear algebra functions.
### Step 2: 
Create the square matrix using np.array().
### Step 3: 
Ensure the matrix is square and its determinant is not zero:
### Step 4: 
Use np.linalg.inv(A) to find the inverse of matrix A.
isplay the inverse using print() or store it for further use.
## Program:
#Program to find the inverse of a matrix.
#Developed by:Hemalatha.A 
#RegisterNumber:212224240056
import numpy as np
A=np.array([[6,2,3],[3,1,1],[10,3,4]])
result=np.linalg.inv(A)
print(result)

## Output:
![alt text](<Screenshot 2025-03-30 190725.png>)
## Result:
Thus the inverse of given matrix is successfully solved using python program

