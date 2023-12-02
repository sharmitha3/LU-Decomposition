# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. import numpy as np
2. from scipy package import lu
3. get input from the user
4. Print result

## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: SHARMITHA V
RegisterNumber: 23002259
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: SHARMITHA V
RegisterNumber: 23002259
'''
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
![image](https://github.com/sharmitha3/LU-Decomposition/assets/145974496/c1751134-de0a-44c7-a142-962e45b8fc4c)

![image](https://github.com/sharmitha3/LU-Decomposition/assets/145974496/2cd4eaca-8b28-414c-b23f-5ee664389170)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

