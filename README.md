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
```python
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: v.priyadaarshini
RegisterNumber: 212225040317
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
OneNorm=np.linalg.norm(InputArray,1)
print(OneNorm)
```
```
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: v.priyadaarshini
RegisterNumber: 212225040317
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
TwoNorm=np.linalg.norm(InputArray,2)
print(f"{TwoNorm:.2f}")
```
```
# 3-Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: v.priyadaarshini
RegisterNumber: 212225040317
'''
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
InputArray=np.array(eval(input()))
InfinityNorm=np.linalg.norm(InputArray,np.inf)
print(InfinityNorm)
```
## Output:
### 1-Norm of a Matrix
![alt text](<Screenshot 2026-05-24 191854.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2026-05-24 191918.png>)

### 3- Infinity Norm of a Matrix
![alt text](<Screenshot 2026-05-24 191943.png>)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
