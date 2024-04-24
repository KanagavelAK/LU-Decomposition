# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the package as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print' .
3. Define a package as "from scipy.linalg import lu_factor, lu_solve" and create the variable as 'X' include the package in that variable.
4. print the variable 'X'

## Program:
(i) To find the L and U matrix
```Python
'''Program to find L and U matrix using LU decomposition.
Developed by: Kanagavel A K
RegisterNumber: 212223230096
'''
import numpy as np
from scipy.linalg import lu
a = np.array(eval(input()))
P,L,U = lu(a)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```Python
'''Program to solve a matrix using LU decomposition.
Developed by: Kanagavel A K
RegisterNumber: 212223230096
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A = np.array(eval(input()))
B = np.array(eval(input()))
lu,piv = lu_factor(A)
X = lu_solve((lu,piv),B)
print(X)

```

## Output:
![Screenshot 2024-04-24 102848](https://github.com/KanagavelAK/LU-Decomposition/assets/151514454/06620482-2c1e-4c5a-8908-b5bb35a85b11)

![Screenshot 2024-04-24 102907](https://github.com/KanagavelAK/LU-Decomposition/assets/151514454/c9fe21bf-ed84-411c-b5a5-7e43e5daf75c)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

