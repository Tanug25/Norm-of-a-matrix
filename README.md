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
# Register No:23004953
# Developed By:Tanushree.A
# 1-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)



# 2-Norm of a Matrix
Program to find 2-norm of a matrix.
Developed by: Tanushree.A
RegisterNumber: 23004953
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)






# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_matrix="{:.2f}".format(ans)
print(norm_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>
![norm of matrix op1](https://github.com/Tanug25/Norm-of-a-matrix/assets/138849166/af084a2c-5338-4d2e-9852-146c8687a96f)

### 2-Norm of a Matrix
<br>
<br>
<br>
![norm of matrix op2](https://github.com/Tanug25/Norm-of-a-matrix/assets/138849166/8ec79a24-4143-426c-83cb-ec61b44ed7ea)

### Infinity Norm of a Matrix
<br>
<br>
<br>
![norm of matrix op3](https://github.com/Tanug25/Norm-of-a-matrix/assets/138849166/12cf7944-f304-4d86-bd91-9999d1a69f32)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
