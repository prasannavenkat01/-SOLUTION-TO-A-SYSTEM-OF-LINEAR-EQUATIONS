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
#Developed by: Prasanna v
#RegisterNumber:23006873
import numpy as np
a=[[1,-3],[3,1]]
b=[0,10]
c=np.linalg.solve(a,b)
print(c)
```

## Output:
![Screenshot 2023-11-29 145940](https://github.com/prasannavenkat01/-SOLUTION-TO-A-SYSTEM-OF-LINEAR-EQUATIONS/assets/150702500/be7ba6dc-5b4c-4d14-9b79-ce172b8ff710)

## Result: 
Thus the solutions for the linear equations are successfully solved using python program

