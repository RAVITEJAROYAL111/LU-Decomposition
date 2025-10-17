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

<img width="777" height="609" alt="image" src="https://github.com/user-attachments/assets/ffd44ed3-1d90-42e8-a924-f96b61a12c8f" />


<img width="591" height="430" alt="image" src="https://github.com/user-attachments/assets/eb9750d0-c86b-406a-b377-daf2cfe954f2" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

