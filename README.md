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
# Register No: K.NIVETHA
# Developed By:22009186
# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:K.NIVETHA
RegisterNumber: 22009186
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,1)
print("{:.2f}".format(n))

# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:K.NIVETHA
RegisterNumber: 22009186
'''
import numpy as np
array=np.array(eval(input()))
n=np.linalg.norm(array,2)
print("{:.2f}".format(n))

# Infinity Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by:K.NIVETHA
RegisterNumber: 22009186
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
![NORM](https://user-images.githubusercontent.com/119559844/215287039-6d883b5e-c92f-47f4-908d-99b493c24466.png)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
