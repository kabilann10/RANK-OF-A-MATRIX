# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: End the program
## Program:'''import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
r=np.linalg.matrix_rank(A)
print(r)'''
## Output:
<img width="1471" height="708" alt="{B8EEF38A-D243-4C4D-A5D6-FE53F9041779}" src="https://github.com/user-attachments/assets/557718e0-227f-4c34-85d9-62e2dbb23260" />
<img width="1123" height="276" alt="{D98E087F-9E99-4848-87CA-298B726DEEA7}" src="https://github.com/user-attachments/assets/ece6d679-153e-437d-88a2-50cc8daf8e91" />

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

