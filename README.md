# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  
Import the numpy module to use the built-in function for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
End the program
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Goutham K
#RegisterNumber:23008975
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank = np.linalg.matrix_rank(A)
print(rank)
```
## Output:
![image](https://github.com/Goutham2306/RANK-OF-A-MATRIX/assets/138971154/22c96bf6-adba-49a2-bc0b-2ec0ecab77c3)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

