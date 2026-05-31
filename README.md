# -SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS
## Aim:
To write a python program to find a solution to a system of linear equations.
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the np.linalg.solve(), we can find the solutions.
### Step 4: 
End the program
## Program:

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"

import numpy as np
A = np.array([[1, 3],
              [2, 5]])
              
B = np.array([5, -3])
C = np.linalg.solve(A,B)

print(C)

## Output:

<img width="888" height="861" alt="image" src="https://github.com/user-attachments/assets/d96aac0f-7ab7-4456-9dd5-4beb47b9b1bb" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

