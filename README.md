# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Define the package as scipy.linalg import lu.

2.Get input from user and print L and U matrix by 'print'

3.Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.

4.print the variable 'X' 

## Program:
(i) To find the L and U matrix
```
'''program to find L and U matrix using LU decompostition.
Develeped by : chaithanya.c
RegisterNumber:2305002004
'''
#To print L and U matrix
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''program to find L and U matrix using LU decompostition.
Develeped by : Deekshitha
RegisterNumber:2305002005
'''
#To print X matrix(solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![image](https://github.com/chaithanyareddychowla/LU-Decomposition/assets/165985172/ac6cedb3-461a-4678-aa5e-bbfa91ffb753)
![image](https://github.com/chaithanyareddychowla/LU-Decomposition/assets/165985172/878c2c80-b080-47ed-9fdb-eb502a47de1d)




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

