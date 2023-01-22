# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import numpy package

2.Import scipy.linalg package to solve LU decomposition

3.Get the input of the matrix

4.Print the result

## Program:
(i) To find the L and U matrix
```

Program to find the L and U matrix.
Developed by: Lakshman reddy
RegisterNumber: 22004423

import numpy as np
from scipy.linalg import lu
A=np.array(eval(input()))
P,L,U=lu(A)
print(L)
print(U)
```

(ii) To find the LU Decomposition of a matrix
```

Program to find the LU Decomposition of a matrix.
Developed by: Lakshman reddy
RegisterNumber: 22004423

# To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
a=np.array(eval(input()))
b=np.array(eval(input()))
lu,piv=lu_factor(a)
x=lu_solve((lu,piv),b)
print(x)
```

## Output:
![Screenshot (24)](https://user-images.githubusercontent.com/118707265/213905572-634547b5-18c0-4b67-975a-72d6fd69c05d.png)
![Screenshot (25)](https://user-images.githubusercontent.com/118707265/213905591-0dbc7ace-1e4d-47c4-9051-42844df79407.png)


## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

