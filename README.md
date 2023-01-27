# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:

Step 1
Import the numpy module to use the built-in functions for calculation

Step 2
Prepare the lists from each linear equations and assign in np.array()

Step 3
Using the np.linalg.solve(), we can find the solutions.

Step 4
End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: C Saravanan
RegisterNumber: 22008175
*/
```
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: C Saravanan
RegisterNumber:  22008175
*/
```
import numpy as np
from scipy.linalg  import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)

## Output:
(i)
![image](https://user-images.githubusercontent.com/121395849/215155585-10cb3786-5324-4442-89f9-9cbf69038512.png)
(ii)
![image](https://user-images.githubusercontent.com/121395849/215155719-df4d6604-8b2c-4791-bc50-84a35153d8bd.png)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

