# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define the packages as scipy.linalg import lu.
2. Get input from user and print L and U matrix by 'print'.
3. Define a package as "from scipy.linalg import lu_factor,lu_solve" and create the variable as 'X' include the package in that variable.
4. Print the variable'X'.

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: Santhiya B
RegisterNumber: 24900724
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
piv,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
'''Program to solve a matrix using LU decomposition.
Developed by: Santhiya B
RegisterNumber: 24900724
'''

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
matrix=np.array(eval(input()))
b=np.array(eval(input()))
x=lu_factor(matrix)
solution=lu_solve(x,b)
print(solution)
*/
```

## Output:
![lu decomposition]![Alt text](<Screenshot from 2024-12-08 12-55-46.png>)
![Alt text](<Screenshot from 2024-12-08 13-34-38.png>)

## Result:Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

