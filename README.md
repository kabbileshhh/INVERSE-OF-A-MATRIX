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
#Program to find the inverse of a matrix.
#Developed by: KABBILESH.S
#RegisterNumber: 212225240063
import numpy as np
A=np.array([
    [1,0,3],
    [-1,2,-2],
    [2,3,-1]])
soln=np.linalg.inv(A)
print(soln)
```

## Output:
<img width="1901" height="919" alt="Screenshot 2026-02-06 085639" src="https://github.com/user-attachments/assets/93340921-1d20-4c24-b23c-fc779f7d6ee5" />


## Result:
Thus the inverse of given matrix is successfully solved using python program

