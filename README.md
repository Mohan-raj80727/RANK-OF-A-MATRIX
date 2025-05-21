# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the NumPy module to access linear algebra functions.
### Step 2:
Create a matrix using np.array() with the desired rows and columns.
### Step 3:
Use np.linalg.matrix_rank() to compute the rank of the matrix.
### Step 4:
Display the rank using a print statement.
## Program:
~~~python
#Program to find the rank of a matrix.
#Developed by: Mohan Raj.s
#RegisterNumber:212224100036


import numpy as np
a=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
solution=np.linalg.matrix_rank(a)
print(solution)
~~~
## Output:
![image](https://github.com/user-attachments/assets/743e4cba-bd2a-4540-9af1-aee794a1ef59)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

