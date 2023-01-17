# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. In the first step to find lu decomposition we using import numpy as np
2. Next we using scipy.linalg for import
3. Next we settimg the variable name
4. Finally printing the value 

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Kavinesh M
RegisterNumber: 22008476
*/
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Kavinesh M
RegisterNumber: 22008476
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A =np.array(eval(input()))
B =np.array(eval(input()))
lu ,piv =lu_factor(A)
x =lu_solve((lu,piv),B)
print(x)
```

## Output:
![lu decomposition](lu1.png)


![ludecomposition](lu2.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

