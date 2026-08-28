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
## Program

```
#Program to find the rank of a matrix.
#Developed by: R.Bharathkumar
#RegisterNumber: 212224103001
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=([[1, 2, 3], [3, 6, 9]])
rank=np.linalg.matrix_rank(A)
print(rank)
```
## Output:
<img width="1917" height="1077" alt="image" src="https://github.com/user-attachments/assets/fe56fc4a-e9e9-42b4-9c72-369a97b65aea" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

