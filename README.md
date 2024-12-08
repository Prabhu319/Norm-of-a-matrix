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
# Register No:24900428
# Developed By:prabanjan.m
# 1-Norm of a Matrix
```
import numpy as np 
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-12-07 144635](https://github.com/user-attachments/assets/10bb2ff8-5e4b-4bd2-a562-e59f3a8fc866)

### 2-Norm of a Matrix
![image](https://github.com/user-attachments/assets/9ea4c7fd-53a4-4936-a550-aecd844aae4c)

### 3-infinity norm fo matrix
![image](https://github.com/user-attachments/assets/ec37ee13-3db9-4d00-8d16-07e221773d07)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
