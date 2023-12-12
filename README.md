# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
import numpy as np:This imports numpy library and gives it the alias np for convenience
### Step 2: 
The next line creates a numpy array representing the matrix[[3,2,5]],[[1,1,2]],[[3,3,6]]
### Step 3:
 Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
finally print(B),this line prints the calculated rank of the matrix to the console
## Program:
``````
#Program to find the rank of a matrix.
#Developed by: GAYATHRI.K
#RegisterNumber:23013439
import numpy as np
A=[[3,2,5],[1,1,2],[3,3,6]]
B=np.linalg.matrix_rank(A)
print(B)
``````
## Output:
![Alt text](<Screenshot 2023-12-12 211456-1.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

