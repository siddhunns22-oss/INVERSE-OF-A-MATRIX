# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import tha numpy module to use the built-in functions for calculation
### Step 2: prepare the lists from each linear equations and assign in np.array()
### Step 3: Using the np.linalg.inv(),we can find the inverse of the given matrix.
### Step 4: End the program

## Program:
#Program to find the inverse of a matrix.
#Developed by: SIDDHARTH N N 
#RegisterNumber:212225240148
import os
os.environ["OPENBLAS_NUM_THREADS"]= "1"
import numpy as np
matrix=np.array([[1,0,3],[-1,2,-2],[2,3,-1]])
result = np.linalg.inv(matrix)
print(result)
## Output:
<img width="1049" height="769" alt="Screenshot 2026-05-05 131942" src="https://github.com/user-attachments/assets/cc329329-5f7a-442e-8d3d-2c312f516bf6" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

