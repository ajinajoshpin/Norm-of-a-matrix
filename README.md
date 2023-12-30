# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
## step 1:
Get the input matrix using np.array()   

 ## step 2:
 Find the 2-norm of the matrix using np.linalg.norm()

 ##  step 3:
  Print the norm of the matrix in two decimal places.
  
## Program:
 ## i) Write a python program to find the 1-Norm of a matrix and display the results in two decimal places.
'''

Program to find 1-norm of a matrix.

Developed by :ajina joshpin

Register number:23013547

'''

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

Norm_of_matrix="{:.2f}".format(ans)

print(Norm_of_matrix)

## ii)Write a program to find 2-norm of a matrix and display the result in two decimal places.
'''
Program to find 2-norm of a matrix.

Developed by: ajina joshpin

RegisterNumber: 23013547

'''

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,2)

Norm_of_matrix="{:.2f}".format(ans)

print(Norm_of_matrix)

## iii)Write a program to find the Infinity of a matrix and display the result in two decimal places.

'''

Program to find 2-norm of a matrix.

Developed by: ajina joshpin

RegisterNumber: 23013547

'''

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,np.inf)

Norm_of_matrix="{:.2f}".format(ans)

print(Norm_of_matrix)

## Output:
### 1-Norm of a Matrix
![image](https://github.com/ajinajoshpin/Norm-of-a-matrix/assets/148514578/fae57fcb-c2f4-4ed1-ba62-0f5a506f443f)

### 2-Norm of a Matrix
![image](https://github.com/ajinajoshpin/Norm-of-a-matrix/assets/148514578/a4a10b45-160b-481f-83e5-6373d5f6c902)

### Infinity Norm of a Matrix
![image](https://github.com/ajinajoshpin/Norm-of-a-matrix/assets/148514578/8ac0aaec-5c5c-41ea-a814-43a0cb6b1eae)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
