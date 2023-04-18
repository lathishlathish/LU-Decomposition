# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Import numpy library using import statement

2.From scipy package import lu_factor() and lu_solve().

3.Get two inputs from user and pass it as matrix array.

4'Find lu and pivot value of first marix using lu_factor().

5.Find solution of the matrix by using lu_solve() by passing lu, pivot values as first argument and second matrix as second argument.

6.Print the solution.

## Program:
(i) To find the L and U matrix
```
#Program to find the L and U matrix.
Developed by: LATHISH KANNA .M
RegisterNumber: 212222230073
import numpy as np
from scipy.linalg import lu
A = np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)

```
(ii) To find the LU Decomposition of a matrix
```
#Program to find the LU Decomposition of a matrix.
Developed by: LATHISH KANNA. M
RegisterNumber: 212222230073
import numpy as np
from scipy.linalg import lu_factor , lu_solve 
A= eval(input()) #np .array (eval(input()))
b=eval(input())
lu,piv = lu_factor(A)
x = lu_solve((lu, piv), b)
print (x)

```
## Output:
![image](https://user-images.githubusercontent.com/120359170/232738927-8ab11e45-476d-4333-b2a2-bf38349a9e20.png)
![image](https://user-images.githubusercontent.com/120359170/232737909-6d4af4e2-6477-45cf-8bd5-c1c917f0c8d4.png)
## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

