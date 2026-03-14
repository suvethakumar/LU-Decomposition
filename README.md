# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.FINDING THE 'L' AND 'U' MATRIX :
STEP1 : Import the numpy module to use the built-in functions for calculation.

STEP2 : Prepare the lists from each linear equations and assign in np.array().

STEP3 :  Using the P,L,U =lu(), we get two results (first is L and second is U) of the given matrix.

STEP4 : end the program

2.FINDING DECOMPOSITION OF THE MATRIX:

STEP1 : Import the numpy module to use the built-in functions for calculation.

STEP2 : Prepare the lists from each linear equations and assign in np.array().

STEP3 : Using the pivot=lu_factor(A) andx=lu_solve((lu,pivot),B) , we can find results  the LU Decomposition of a matrix

STEP4 : end the program

## Program:
~~~ python

#Register no:212225040444
#developed by:Suvetha.k

(i) To find the L and U matrix:

import numpy as np

from scipy.linalg import lu

a=np.array(eval(input()))

P,L,U=lu(a)

print(L)

print(U)

(ii) To find the LU Decomposition of a matrix
import numpy as np

from scipy.linalg import lu_factor,lu_solve

A=np.array(eval(input()))

B=np.array(eval(input()))

lu,pivot=lu_factor(A)

x=lu_solve((lu,pivot),B)

print(x)
~~~
## Output:
<img width="1235" height="594" alt="Screenshot 2026-02-05 163526" src="https://github.com/user-attachments/assets/8d27d974-f7f3-4ece-a4b5-99a6013d8322" />

<img width="995" height="321" alt="Screenshot 2026-02-05 163547" src="https://github.com/user-attachments/assets/c9365987-bdc0-4416-baef-147a62ab64c5" />

## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

