# LU Decomposition 

NAME : P.JESHWANTH KUMAR
REF.NO : 212223240114

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Start the program
2. from scipy.linalg lib import L an U matrix  and numpy as np
3. get input from the user in arraay format
4. get the result

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: P.Jeshwanth Kumar
RegisterNumber: 23002519
'''
from scipy.linalg import lu
import numpy as np
arr=eval(input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: P.Jeshwanth Kumar
RegisterNumber: 23002519
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

*/
```

## Output:
![image](https://github.com/Jeshwanthkumarpayyavula/LU-Decomposition/assets/145742402/c8252e5e-f507-444d-a13e-726c33499afa)
![image](https://github.com/Jeshwanthkumarpayyavula/LU-Decomposition/assets/145742402/51c74428-55b9-4721-9396-a9e0165aa584)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

