# INVERSE-OF-A-MATRIX
## Aim:
To write a python program to find the inverse of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : Import the numpy module to use the built-in functions for calculation
### Step 2: Prepare the lists from each linear equations and assign in np.array()
### Step 3: Using np.linalg.inv(),we can find the inverse of a matrix
### Step 4: End the program

## Program:
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np 
A=np.array([[2,1,1],[1,1,1],[1,-1,2]])
r=np.linalg.inv(A)
print(r)
```
## Output:
<img width="1447" height="753" alt="image" src="https://github.com/user-attachments/assets/7d69ecbb-88aa-44c0-b613-74679b5a2cfc" />
<img width="1281" height="296" alt="image" src="https://github.com/user-attachments/assets/ea9e9447-e852-4bc8-bf1f-897beffaa939" />

## Result:
Thus the inverse of given matrix is successfully solved using python program

