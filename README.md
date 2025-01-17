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
```
# Register No:23003406
# Developed By:narra akhil
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
print("{:.2f}".format(ans)

# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: Narra Akhil
RegisterNumber: 23003406
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
print("{:.2f}".format(ans))

# 3-Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
print("{:.2f}".format(ans))
```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/NARRAAKHIL/Norm-of-a-matrix/assets/144979843/dc16bed6-b0b5-446a-b400-a83a7bc76068)
### 2-Norm of a Matrix
![image](https://github.com/NARRAAKHIL/Norm-of-a-matrix/assets/144979843/e51f4267-936c-446e-8ebe-164e5793f07c)
### Infinity Norm of a Matrix
![image](https://github.com/NARRAAKHIL/Norm-of-a-matrix/assets/144979843/e243a553-11ce-4be2-99f0-c9fb8623be55)
## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
