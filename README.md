# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1:  
Import required libraries `numpy` and `scipy.linalg`.  

### Step 2:  
Input the matrix/matrices using `eval(input())`.  

### Step 3:  
Perform LU decomposition using `lu()` or solve equations using `lu_factor()` and `lu_solve()`.  

### Step 4:  
Print the results `L` and `U` matrices or solution `X` matrix.  

## Program:
(i) To find the L and U matrix
```
#Program to find L and U matrix using LU decomposition.
#Developed by: DHARSHINI S N 
#RegisterNumber: 212224230062

import numpy as np
from scipy.linalg import lu
A= np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
#Program to solve a matrix using LU decomposition.
#Developed by: DHARSHINI S N 
#RegisterNumber: 212224230062

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a= np.array(eval(input()))
b= np.array(eval(input()))
l,p=lu_factor(a)
x=lu_solve((l,p),b)
print(x)
```

## Output:
(i) To find the L and U matrix
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/16575539-29d5-4b69-9f3c-d2da11fcbc2c" />
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/87626b25-5a3d-4896-8e74-2eb45c3b67dd" />


(ii) To find the LU Decomposition of a matrix
<img width="1920" height="1200" alt="image" src="https://github.com/user-attachments/assets/4c67f2ef-aaf3-444c-9173-2acec87db183" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

