# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
### Step 2: 
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: 
## Program:
```
#Program to find the rank of a matrix.
#Developed by: Induja R
#RegisterNumber: 212225230103

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
matrixA=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(matrixA)
print(rank)

```
## Output:

<img width="1027" height="668" alt="image" src="https://github.com/user-attachments/assets/4212662a-1acf-4f74-8070-82707e9f1e63" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

