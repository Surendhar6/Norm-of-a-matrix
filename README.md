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

i) # 1-Norm of a Matrix
```
'''
Write a python program to find the 1-Norm of a matrix 
Register No.: 212222110049
Developed By: Surendhar A
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

ii) # 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

iii) # Infinity Norm of a Matrix
```
'''
program to find the Infinity of a matrix.
Developed by: Surendhar A
RegisterNumber: 212222110049
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![image](https://github.com/Surendhar6/Norm-of-a-matrix/assets/118352907/0febb3ce-c57b-4224-8b5b-e45225a3c190)

### 2-Norm of a Matrix
![image](https://github.com/Surendhar6/Norm-of-a-matrix/assets/118352907/c63334c1-7a24-4153-b64f-b913786fc75b)

### Infinity Norm of a Matrix
![image](https://github.com/Surendhar6/Norm-of-a-matrix/assets/118352907/cef667b3-ef2c-4716-a46a-0b2021600f71)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
