# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step 1: 
Import the numpy module to use the built-in functions for calculation
### Step 2: 
Prepare the lists from each linear equations and assign in np.array()
### Step 3: 
Using the appropriate command, we can find the solutions.
### Step 4: 
End the program 

## Program:
(i) To find the L and U matrix

Program to find the L and U matrix.
```
import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

Developed by: Priyadharshini V
RegisterNumber: 25018161


(ii) To find the LU Decomposition of a matrix


Program to find the LU Decomposition of a matrix.

```
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=np.array(eval(input()))
B=np.array(eval(input()))
lu,pivot=lu_factor(A)
x=lu_solve((lu,pivot),B)
print(x)
```
Developed by: Priyadharshini V
RegisterNumber: 25018161


## Output:
L and U matrix
<img width="1920" height="1080" alt="Screenshot 2025-12-24 222432" src="https://github.com/user-attachments/assets/ae54fb22-d526-4414-bfa2-b5ca6e071479" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 222441" src="https://github.com/user-attachments/assets/c3ee1a79-beda-4544-9c8b-744c42df93fe" />
LU Decomposition of a matrix
<img width="1920" height="1080" alt="Screenshot 2025-12-24 222451" src="https://github.com/user-attachments/assets/5aa86c61-d69c-4b6a-9012-46d1ddf5918a" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 222501" src="https://github.com/user-attachments/assets/b9241b31-88e6-4a3a-a72f-28867a50c74a" />



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

