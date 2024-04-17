# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import lu(),lu_factor() and lu_solve() from scipy.linalg library.
2. Use lu() method to find lower and upper matrix.
3. Use lu_factor() and lu_solve to solve the two matrixes.
4. End the program.

## Program:
(i) To find the L and U matrix
'''Program to find L and U matrix using LU decomposition.
Developed by: Pragadeeswaran L
RegisterNumber: 212223240120
'''
import numpy as np
from scipy.linalg import lu
matrix=np.array(eval(input()))
pivot,l_matrix,u_matrix=lu(matrix)
print(l_matrix)
print(u_matrix)
(ii) To find the LU Decomposition of a matrix
'''Program to solve a matrix using LU decomposition.
Developed by: Pragadeeswaran L
RegisterNumber: 212223240120
'''

# To print X matrix (solution to the equations)
import numpy as np
import scipy.linalg as la
A=np.array(eval(input()))
B=np.array(eval(input()))
LU,piv=la.lu_factor(A)
x=la.lu_solve((LU,piv),B)
print(x)

## Output:
(i)
![image](https://github.com/Pragadeeswaran-bit/LU-Decomposition/assets/147473828/dab9a638-cfb5-4ddf-ada3-ea3a69bdfe19)
![image](https://github.com/Pragadeeswaran-bit/LU-Decomposition/assets/147473828/bb1fa629-39a2-43a3-925d-229fbd36d61a)
(ii)
![image](https://github.com/Pragadeeswaran-bit/LU-Decomposition/assets/147473828/f51c425e-bb6a-467b-934f-3a11181532da)
![image](https://github.com/Pragadeeswaran-bit/LU-Decomposition/assets/147473828/a1fb9a18-f260-43a8-bce8-521832fd1532)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

