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

## Output:<img width="851" height="589" alt="image" src="https://github.com/user-attachments/assets/3c7ba47c-44d1-469c-8558-d26adbbf3ac1" />
<img width="811" height="685" alt="image" src="https://github.com/user-attachments/assets/d911f531-57ba-4314-93cc-cb0115420a0f" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

