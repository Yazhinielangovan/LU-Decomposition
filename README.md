## EXPERIMENT NO.: 05
## DATE : 30.03.2024

# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs.
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner.

## Algorithm
1. import numpy.
2. From scipy.linalg import lu ,lu_factor,lu_solve respectively.
3. Get the input of matrix values from user using eval.
4. Using P,L,U=lu(A) we can find L and U matrix . Using res=lu_factor(A) ,solution=lu_solve(res,B) we can find LU Decomposition of a matrix.
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by:YAZHINI  
RegisterNumber: 2305002028
import numpy as np 
from scipy.linalg import lu 
A = np.array(eval(input())) 
P,L,U=lu(A) 
print(L)
print(U) 
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: YAZHINI 
RegisterNumber: 2305002028
import numpy as np 
from scipy.linalg import lu_factor,lu_solve 
A = np.array(eval(input()))
b = np.array(eval(input()))
lu,piv = lu_factor(A)
x = lu_solve((lu,piv),b)
print(x)
*/
```

## Output:
![image](https://github.com/Yazhinielangovan/LU-Decomposition/assets/155508323/b80f062d-a872-4891-b494-4a5e6d605fab)

![image](https://github.com/Yazhinielangovan/LU-Decomposition/assets/155508323/193e41c5-a1eb-4ed9-bdc6-9ac4bc49ff9f)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

