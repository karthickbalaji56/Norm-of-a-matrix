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
# Register No:212225040174
# Developed By:KARTHICK BALAJI S
# 1-Norm of a Matrix
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

# Input matrix
A = eval(input())

# Find 1-Norm
norm1 = np.linalg.norm(A, 1)

# Display result in two decimal places
print("{:.2f}".format(norm1))




# 2-Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np


# Input matrix
A = eval(input())

# Find L2-Norm (Spectral Norm)
norm2 = np.linalg.norm(A, 2)

# Display result in two decimal places
print("{:.2f}".format(norm2))





# Infinity Norm of a Matrix

import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np
A = eval(input())
norm_inf = np.linalg.norm(A, np.inf)
print("{:.2f}".format(norm_inf))




```
## Output:
### 1-Norm of a Matrix
<img width="598" height="214" alt="image" src="https://github.com/user-attachments/assets/e19f9f78-9603-49f2-9167-1e8967b27c7a" />


### 2-Norm of a Matrix
<img width="636" height="284" alt="image" src="https://github.com/user-attachments/assets/01a9bc79-242b-4590-a140-264a5f1957bc" />



### Infinity Norm of a Matrix
<img width="588" height="208" alt="image" src="https://github.com/user-attachments/assets/b223140f-5485-41f4-8696-6a78273db565" />


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
