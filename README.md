# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.

## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.

## Program:
```Python
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix. 
Developed by: Chandru M
RegisterNumber:  212224230041
'''

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,1)
print(result)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Chandru M
RegisterNumber: 212224230041
'''
import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,2)
print(f"{result:.2f}")



# Infinity Norm of a Matrix

'''
Program to find the Infinity norm of the matrix.
Developed By : Chandru M
Register Number : 212224230041
'''

import numpy as np
matrix=np.array(eval(input()))
result=np.linalg.norm(matrix,np.inf)
print(result)



```
## Output:
### 1-Norm of a Matrix

![output1](image-1.png)

### 2-Norm of a Matrix

![output](image.png)

### Infinity Norm of a Matrix

![output2](image-2.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
