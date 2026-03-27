# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
# 1-Norm of a Matrix
```
Step 1: Start
Step 2: Import the NumPy library
Step 3: Read the matrix input from the user
Step 4: Convert the input into a NumPy array
Step 5: Find the absolute values of all elements in the matrix
Step 6: Compute the sum of absolute values for each column
Step 7: Find the maximum among these column sums
     This value is the 1-norm of the matrix
Step 8: Format the result to 2 decimal places
Step 9: Display the result
Step 10: Stop
```
# 2-Norm of a Matrix
```
Step 1: Start
Step 2: Import the NumPy library
Step 3: Read the matrix input from the user
Step 4: Convert the input into a NumPy array
Step 5: Compute A^TA (transpose of matrix × matrix)
Step 6: Find the eigenvalues of A^TA
Step 7: Select the maximum eigenvalue
Step 8: Take square root of the maximum eigenvalue
   This gives the 2-norm (spectral norm)
Step 9: Format the result to 2 decimal places
Step 10: Display the result
Step 11: Stop
```
# 3-Infinity Norm of a Matrix
```
Step 1: Start
Step 2: Import the NumPy library
Step 3: Read the matrix input from the user
Step 4: Convert the input into a NumPy array
Step 5: Find the absolute values of all elements in the matrix
Step 6: Compute the sum of absolute values for each row
Step 7: Find the maximum among these row sums
   This value is the Infinity Norm
Step 8: Format the result to 2 decimal places
Step 9: Display the result
Step 10: Stop
```
## Program:
```
# Register No: 212225230182
# Developed By: Mohana Priya D
```
# 1-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```
# 2-Norm of a Matrix
```python
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)
```

# 3-Infinity Norm of a Matrix
```python
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
