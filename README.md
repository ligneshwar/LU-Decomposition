# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linnalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve"and create the variable as'X'include the package in that variable. 
4. print the variable'X'
   

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: K.Ligneshwar
RegisterNumber: 212223230113
*/
from scipy.linalg import lu
import numpy as np
arr=eval(input())
a=np.array(arr)
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:K.Ligneshwar
RegisterNumber:212223230113
*/
from scipy.linalg import lu_factor,lu_solve
import numpy as np
arr=eval(input())
constant=eval(input())
a=np.array(arr)
b=np.array(constant)
result=lu_factor(a)
solution=lu_solve(result,b)
print(solution)
```

## Output:

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

