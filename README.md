# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy as np and from scipy import lu

2.Get the input of array from the user

3.solve P,L,U and print the values

4.End the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: N.Kishore
RegisterNumber: 212222240049
*/
import numpy as np
from scipy.linalg import lu
arr=eval(input())
P,L,U=lu(arr)
print(L)
print(U)
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: N.Kishore
RegisterNumber: 212222240049
*/
import numpy as np
from scipy.linalg import lu_factor,lu_solve
arr=np.array([[3,2,7],[2,3,1],[3,4,1]])
B=np.array([4,5,7])
LU,P=lu_factor(arr)
res=lu_solve((LU,P),B)
print(res)
```

## Output:

![Screenshot 2023-06-03 174853](https://github.com/nkishore2210/LU-Decomposition/assets/118707090/b544eef4-7d3f-4396-b7a7-58f9b6f1f8b5)

![Screenshot 2023-06-03 174907](https://github.com/nkishore2210/LU-Decomposition/assets/118707090/b90c7ab2-2d6e-4333-b03b-581306cfaea7)

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

