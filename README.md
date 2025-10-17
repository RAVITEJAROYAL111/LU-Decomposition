# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. ### Step 1:
import numpy as np
### Step 2:
from scipy package import lu
### Step 3:
get input from the user
### Step 4:
print result
## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: A.RAVI TEJA ROYAL
RegisterNumber: 25011599
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U = lu(A)
print(L)
print(U)
```
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: RAVI TEJA ROYAL
RegisterNumber:25011599 
*/
```# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu, piv = lu_factor(A)
x = lu_solve((lu, piv),B)
print(x)

## Output:
![lu decomposition]()
<img width="806" height="563" alt="image" src="https://github.com/user-attachments/assets/1a574658-780a-423f-a767-e0939126742a" />
<img width="551" height="477" alt="image" src="https://github.com/user-attachments/assets/acac1949-ce46-4365-abb7-23c6108987bb" />
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

