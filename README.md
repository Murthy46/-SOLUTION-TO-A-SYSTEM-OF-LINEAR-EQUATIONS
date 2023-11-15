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
#Program to find the solution for the given linear equations.
#Developed by:sundaramurthy M
#RegisterNumber:212222233006

import numpy as np
a=np.array([[1,3],[2,5]])
b=np.array([5,-3])
result=np.linalg.solve(a,b)
print(result)
```

## Output:
<img width="1440" alt="Screenshot 2023-11-15 at 9 26 01 PM" src="https://github.com/Murthy46/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/145112768/ed853fbe-169c-4f9a-a236-26c0a630ce0e">



## Result: 
Thus the solutions for the linear equations are successfully solved using python program

