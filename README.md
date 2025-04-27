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
# Register No: 212224230044
# Developed By: CHARUKESH S
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# 2-Norm of a Matrix

import numpy as np
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/user-attachments/assets/8abab752-23af-4fd4-956b-e44f52adc6c8)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/7c76fce1-0d43-4cd1-898e-5a2a3fc04752)

### Infinity Norm of a Matrix
![image](https://github.com/user-attachments/assets/a2719900-2621-4df0-ab5f-2df0922dedf5)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
