# Gaussian Elimination

## AIM:
To write a program to find the solution of a matrix using Gaussian Elimination.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Get the matrix from user.

2. Using "from numpy as np sys" to import numpy (Ge).

3. Print the result matrices (Gaussian Elimination).

4. End the program. 


## Program:
~~~
Program to find the solution of a matrix using Gaussian Elimination.
Developed by:R.Brindha
RegisterNumber:22008265
import numpy as np
import sys
n = int(input())
a = np.zeros((n,n+1))
x = np.zeros(n) 

for i in range(n):
    for j in range(n+1):
        a[i][j] = float(input()) 
        
for i in range(n):
    if a[i][j]==0.0:
        sys.exit('divide by zero detected!')
~~~

## Output:
![output](./G.E%20OUTPUT.png)


## Result:
Thus the program to find the solution of a matrix using Gaussian Elimination is written and verified using python programming.

