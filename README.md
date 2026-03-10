# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm

1. Import required libraries: NumPy and SciPy for matrix operations and LU decomposition.
2. Read the input matrix and perform LU decomposition using lu() to obtain P, L, U matrices.
3. Print the Lower triangular matrix (L) and Upper triangular matrix (U).
4. Define matrix A and vector B representing the system of equations. 𝐴𝑋=𝐵
5. Use lu_factor() to factorize A and lu_solve() to compute and print the solution vector X.

## Program:
(i) To find the L and U matrix
```
/*
Program to find L and U matrix using LU decomposition.
Developed by : VIGNESH J 
ReferenceNumber : 25014705
RegisterNumber: 212225230297
import numpy as np
from scipy.linalg import lu
data = eval(input())
P,L,U = lu(data) 
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to solve a matrix Using LU Decomposition 
Name :  VIGNESH J
ReferenceNumber : 25014705
RegisterNumber : 212225230297
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg  import lu_factor,lu_solve
a = np.array([[3, 2, 7], [2, 3, 1], [3, 4, 1]])
b = [4, 5, 7]
lu,piv = lu_factor(a)
print(lu_solve((lu,piv),b))
*/
```
## Output:
![lu decomposition]()

<img width="789" height="919" alt="Screenshot 2026-03-10 084600" src="https://github.com/user-attachments/assets/9f1c44f4-b784-44b0-9c51-487ca34ff72d" />

<img width="741" height="916" alt="Screenshot 2026-03-10 084621" src="https://github.com/user-attachments/assets/09a86a0b-3864-4561-9cc9-9a6d7637ee6c" />




## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

