# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## Step 1: 
Start the program.
## Step 2: 
Import the required library numpy for matrix operations.
## Step 3: 
Using the np.linalg.matrix_rank() function, find the rank of the given matrix.
## Step 4: 
Display the rank of the matrix.
## Step 5: 
Stop the program.
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

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/15a00398-ea9c-4fdd-83f0-c9d0b5e8dca2" />

[text](exp2.rev.pdf)
  



## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

