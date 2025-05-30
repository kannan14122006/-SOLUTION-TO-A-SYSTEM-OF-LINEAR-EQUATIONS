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
#Program to find the solution for the given linear equations.

#Developed by: kannan R
#RegisterNumber: 212224240072

```import numpy as np

A = np.array([[1, -3], [3, 1]])  # Coefficient matrix

B = np.array([0, 10])  # Constants on the right-hand side

solution = np.linalg.solve(A, B)

print(solution)
```
## Output:
![image](https://github.com/user-attachments/assets/9acd370a-78cb-4e4f-81de-7420f101a53b)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

