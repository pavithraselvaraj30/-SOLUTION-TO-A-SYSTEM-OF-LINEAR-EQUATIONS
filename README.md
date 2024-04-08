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
#Developed by: Pavithra.S
#RegisterNumber:212223230147
import numpy as np
A=np.array([[1,-3],[3,1]])
B=np.array([0,10])
le=np.linalg.solve(A,B)
print(le)

```
## Output:
![Screenshot 2024-04-08 140625](https://github.com/pavithraselvaraj30/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/149366880/093fad02-67c9-4bef-a496-63d6bbf86dbd)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

