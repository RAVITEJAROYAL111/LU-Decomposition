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


<img width="1254" height="919" alt="292682420-e25eafca-eda8-4d9a-9b1c-b5599b970e49" src="https://github.com/user-attachments/assets/8022d4c9-fc8c-4b39-842d-df59217f1ff8" />

<img width="1257" height="683" alt="292682436-3fc605ce-39cb-4765-a670-80740fc02a31" src="https://github.com/user-attachments/assets/264d688c-91b8-4cef-8e5a-2f30d63b7447" />
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

