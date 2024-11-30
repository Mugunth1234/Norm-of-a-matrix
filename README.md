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
##1-norm of matrix
```
'''
Program to find 1-norm of a matrix.
Developed by: M.Mugunthan
Register Number: 24005593
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
Norm_of_matrix= "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# 2-Norm of a Matrix
```
'''
Program to find 2-norm of a matrix.
Developed by: M.Mugunthan
RegisterNumber: 24005593
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)
```
# Infinity Norm of a Matrix
```
'''
Program to find infinity Norm of a matrix.
Developed by: M.Mugunthan
RegisterNumber: 24005593
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
![Screenshot 2024-11-30 155428](https://github.com/user-attachments/assets/9e365f04-e12c-4ee6-a2cf-7c41cdadbb59)

### 2-Norm of a Matrix

![Screenshot 2024-11-30 155748](https://github.com/user-attachments/assets/3f76fbc4-d5eb-43fc-888d-3c7a115d1317)


### Infinity Norm of a Matrix
![Screenshot 2024-11-30 155612](https://github.com/user-attachments/assets/07006f39-b76f-48fe-82d8-26819ccbdbe0)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
