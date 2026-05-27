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
#Program to find the rank of a matrix.

#Developed by:Eljaa Sam S C 

#RegisterNumber:212225040085

import os

os.environ['OPENBLAS_NUM_THREADS']="1"

import numpy as np

a=np.array( [[3,2,5],[1,1,2],[3,3,6]])

solution=np.linalg.matrix_rank(a)

print(solution)

## Output:
<img width="869" height="185" alt="{72615CE2-A4DF-4AAB-8F25-29924F706A80}" src="https://github.com/user-attachments/assets/e2819012-3d24-45c2-86fc-9d87f3db54c8" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

