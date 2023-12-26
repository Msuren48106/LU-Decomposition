# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
To Find L and U matrices with LU Decomposition Step 1: Get the matrix from the user.
Step 2: Using "from scipy.linalg import lu" to import scipy (LU) module.

Step 3: Using "L,U=lu(a)" we can get the matrix of L and U.

Step 4: Print the result matrices (L and U Matrices).

Step 5: End of the Program.

To Find X matrix with LU Decomposition Step 1: Get the matrix from the user.
Step 2: Using "from scipy.linalg import lu_factor,lu_solve" to import scipy module for factorization and solving X.

Step 3: Using "lu,piv=lu_factor(a)"

Step 4: Print the output(x matrix)

Step 5: End of the Program. 


## Program:
(i) To find the L and U matrix
```
'''Program to find L and U matrix using LU decomposition.
Developed by: M.suren.
RegisterNumber: 23005055
'''
import numpy as np
from scipy.linalg import lu
arr=eval (input())
A=np.array(arr)
P,L,U=lu(A)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
'''Program to solve a matrix using LU decomposition.
Developed by: M.suren.
RegisterNumber: 23005055
'''

# To print X matrix (solution to the equations)
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
![image](https://github.com/Msuren48106/LU-Decomposition/assets/150503875/361505d8-14bd-4ca4-8b1b-750ae014c687)
![image](https://github.com/Msuren48106/LU-Decomposition/assets/150503875/bb075125-218f-4f35-9b5e-8ab3e9bd9317)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

