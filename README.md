# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step 1:

Get the input matrix using np.array()

Step 2:

Find the 2-norm of the matrix using np.linalg.norm()

Step 3:

Print the norm of the matrix in two decimal places.

Step 4:

End the program.
## Program:
```
# Register No:212224220114
# Developed By:SURUTHI S
# 1-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by:SURUTHI S
RegisterNumber:212224220114
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
norm_of_matrix = "{:.2f}".format(ans)
print(norm_of_matrix)
# 2-Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SURUTHI S
RegisterNumber: 212224220114
'''
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,2)
norm_of_matrix='{:.2f}'.format(ans)
print(norm_of_matrix)
# Infinity Norm of a Matrix
'''
Program to find 2-norm of a matrix.
Developed by: SURUTHI S
RegisterNumber: 212224220114
'''
import numpy as np
mat = np.array(eval(input()))
norm = np.linalg.norm(mat,ord=np.inf)

print('{:.2f}'.format(norm))
```
## Output:
## 1-Norm of a Matrix

![Screenshot 2025-05-05 160042](https://github.com/user-attachments/assets/a437586e-8e66-4f2f-86dc-515b92db2079)

## 2-Norm of a Matrix

![Screenshot 2025-05-05 160227](https://github.com/user-attachments/assets/a9a2d4a1-0cd2-44e5-ab6a-76bb0c4a3461)

## Infinity Norm of a Matrix

![Screenshot 2025-05-05 160211](https://github.com/user-attachments/assets/f0b8ab13-3506-4175-8c2c-ebf029b03002)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
