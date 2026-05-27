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
```
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array([
    [1, -3],
    [3, 1],
], dtype=float)

B = np.array([0, 10], dtype=float)

solution = np.linalg.solve(A, B)

print(solution)
```
## Output:
<img width="1288" height="759" alt="image" src="https://github.com/user-attachments/assets/bf5b8ba5-cf1d-4a57-a691-9ab05ce0b0e2" />
<img width="1304" height="297" alt="image" src="https://github.com/user-attachments/assets/9e69a9ad-571f-434e-82a7-a553309ba482" />

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

