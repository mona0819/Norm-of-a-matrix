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
# Register No: 212225230182
# Developed By: Mohana Priya D
```
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

# 3-Infinity Norm of a Matrix
```
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

## Output:
### 1-Norm of a Matrix
<img width="1292" height="357" alt="image" src="https://github.com/user-attachments/assets/5641e1a6-1026-4ff4-b6ad-d5248fc18844" />


### 2-Norm of a Matrix
<img width="1250" height="417" alt="image" src="https://github.com/user-attachments/assets/bf25f3f4-7df1-4c0c-911d-f22b3cbfa610" />


### 3-Infinity Norm of a Matrix
<img width="1231" height="356" alt="image" src="https://github.com/user-attachments/assets/e4a76d8f-7259-4704-a0a9-bd6df0d85ae9" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
