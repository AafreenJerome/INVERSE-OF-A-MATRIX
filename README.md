# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the NumPy module using import numpy as np.
### Step 2: Create a NumPy array containing the elements of the given matrix.
### Step 3: Using the np.linalg.inv() function, find the inverse of the given matrix.
### Step 4: Print the inverse matrix and end the program.

## Program:

Program to find the inverse of a matrix.

Developed by: AAFREEN JEROME

RegisterNumber: 26007104

import os

os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np

a=np.array([[6,2,3],[3,1,1],[10,3,4]])

b=np.linalg.inv(a)

print(b)

## Output:

<img width="967" height="777" alt="image" src="https://github.com/user-attachments/assets/b0872084-ad60-43b2-b483-efdf45a4d539" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

