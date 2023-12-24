# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: vinodini. k
RegisterNumber: 23013556
*/
import numpy as np
from scipy.linalg import lu

A=np.array(eval(input()))
P,L,U= lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: vinodhini . k
RegisterNumber: 23013556
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
A=np.array(arr)
B=np.array(constant)
result=lu_factor(A)
solution=lu_solve(result,B)
print(solution)
```

## Output:
i)
![Alt text](<lu out 1.png>)
ii)
![Alt text](<lu 2 out.png>)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

