# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2.Get input from user and print L and U matrix by 'Print' 
3.Define a package as"from scipy.linalg importlu_factor,ul_solve" and create the variable as'X'
include the package in that variable 
4.Print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:Ganga devi 
RegisterNumber:212224240042 
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
p,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by:Ganga devi 
RegisterNumber:212224240042 
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,piv=lu_factor(A)
X=lu_solve((lu,piv),B)
print(X)
```

## Output:
![Screenshot (148)](https://github.com/user-attachments/assets/8decc743-bbca-4cd3-b21c-747e41514b8a)


![Screenshot (151)](https://github.com/user-attachments/assets/255f2da1-8426-463f-8326-24c7f496097c)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

