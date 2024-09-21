# DATE:
# EXP - 5 LU Decomposition 

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

Program to find the L and U matrix.
Developed by: Saravanan C
RegisterNumber: 212222110041

```
```
import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Saravanan C
RegisterNumber:  212222110041

```
```
import numpy as np
from scipy.linalg  import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```
## Output:
(i)
![Ex-05 CR  LU Decomposition 1](https://github.com/user-attachments/assets/0ac0192e-c874-401d-b624-e62ea3ae1f80)

(ii)

![Ex-05 CR LU Decomposition 2](https://github.com/user-attachments/assets/5953af9f-da9b-46b6-a8d7-67592147a783)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

