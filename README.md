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
Program to find the solution for the given linear Eqautions

Developed by: Srinath YG

Register Number: 212224230274
```python
import numpy as np

A = [[1, 3], [2, 5]]
B = np.array([5, -3])
C = np.linalg.solve(A, B)

print(C)
```
## Output:
![436866895-64de3b7d-e05f-41ba-92ec-4ac8aac2d9f5](https://github.com/user-attachments/assets/9caf855f-96a5-4f6c-834f-fbd092ea7b67)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

