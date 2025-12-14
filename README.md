# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
Step 1:
Import the numpy module to use the built-in functions for calculation
Step 2:
Prepare the lists from each linear equations and assign in np.array()
Step 3:
 using the scripy.linalg import lu,we can find the solutions
Step 4:
 End of the program

## Program:
(i) To find the L and U matrix
```
/*
Program to find the L and U matrix.
Developed by: Renita Ireen G
RegisterNumber:25008430
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```
/*
Program to find the LU Decomposition of a matrix.
Developed by: Renita Ireen G
RegisterNumber:25008430
# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
AMatrix=np.array(eval(input()),dtype='i')
BMatrix=np.array(eval(input()),dtype='i')
XMatrix=lu_factor(AMatrix)
Solution=lu_solve(XMatrix,BMatrix)
print(Solution)
*/
```

## Output:
<img width="1191" height="679" alt="Screenshot 2025-12-14 181502" src="https://github.com/user-attachments/assets/f726efc5-bb26-4f0d-992e-0d9fb7e61e7d" />
<img width="1256" height="575" alt="Screenshot 2025-12-14 181511" src="https://github.com/user-attachments/assets/2f248fd4-fe02-4ec3-a183-e10a30d20b43" />
<img width="1199" height="609" alt="Screenshot 2025-12-14 182117" src="https://github.com/user-attachments/assets/5f894241-d006-40aa-869c-3f0a342b6225" />
<img width="1017" height="334" alt="Screenshot 2025-12-14 182125" src="https://github.com/user-attachments/assets/60a669a5-9a6b-493d-9263-fa0c34d7a0ac" />


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

