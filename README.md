# LU Decomposition 
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: JANANI S
RegisterNumber: 23013409
*/
import numpy as np
from scipy.linalg import lu 
a=np.array(eval(input()))
P,L,U=lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: JANANI S
RegisterNumber: 23013409
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
A=np.array(a)
B=np.array(b)
result=lu_factor(A)
sol=lu_solve(result,B)
print(sol)
```
## Output:
![image](https://github.com/SJananisenthilkumar/LU-Decomposition/assets/144871139/70f9b69d-037d-4b23-a0ff-fb45b696449e)
![image](https://github.com/SJananisenthilkumar/LU-Decomposition/assets/144871139/fe7ec9c5-8cc6-414b-9a92-fce1502f21f3)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

