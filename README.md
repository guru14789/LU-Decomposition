## LU Decomposition
## AIM:
To write a program to find the LU Decomposition of a matrix.
## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm

## (i)To find the L and U matrix
## STEP 1:
Import the numpy module to use the built-in functions for calculation
## STEP 2:
from scipy.linalg module import lu to find the L and U matrix
## STEP 3:
get input from the user and apply lu function
## STEP 4:
print L for L matrix and print U for U matrix
## STEP 5:
End of program

## (ii)To find the LU Decomposition of a matrix
## STEP 1:
Import the numpy module to use the built-in functions for calculation
## STEP 2:
from scipy.linalg module import lu_factor() and lu_solve() to find lu decomposition of the matrix
## STEP 3:
get input from the user
## STEP 4:
apply lu_factor() and lu_solve() functions to get the answer
## STEP 5:
End of program


## Program:
## (i) To find the L and U matrix
```
Program to find L and U matrix using LU decomposition.
Developed by: SREEKUMAR S
RegisterNumber: 23008070 

import numpy as np
from scipy.linalg import lu
a=eval(input())
p,l,u=lu(a)
print(l)
print(u)
```
## (ii) To find the LU Decomposition of a matrix
```
Program to solve a matrix using LU decomposition.
Developed by: SREEKUMAR S
RegisterNumber:23008070

import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=eval(input())
b=eval(input())
lu=lu_factor(a)
x=lu_solve(lu,b)
print(x)

```

## Output:
## (i) To find the L and U matrix
![lu decompostion 1](https://github.com/guru14789/LU-Decomposition/assets/151705853/1ad5cf81-9c7a-4a81-8a98-16312bd72aa3)

## (ii) To find the LU Decomposition of a matrix
![lu decompostion 2](https://github.com/guru14789/LU-Decomposition/assets/151705853/0d5c6adf-4bee-47da-8c9b-d8c573f0b08c)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

