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
# Register No: 212223230151
# Developed By: Prajin S
# 1-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,1)
print('{:.2f}'.format(norm))



# 2-Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,2)
print("{:.2f}".format(norm))



# Infinity Norm of a Matrix
import numpy as np
value=eval(input())
arr=np.array(value)
norm=np.linalg.norm(arr,np.inf)
print('{:.2f}'.format(norm))




```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-12-20 170844](https://github.com/Prajin19/Norm-of-a-matrix/assets/144979377/40db5fa6-1322-4923-b0cd-d49dc1ed6384)

### 2-Norm of a Matrix
![Screenshot 2023-12-20 170907](https://github.com/Prajin19/Norm-of-a-matrix/assets/144979377/28314236-168e-4c9b-a1f4-a426c61bf91d)


### Infinity Norm of a Matrix
![Screenshot 2023-12-20 170928](https://github.com/Prajin19/Norm-of-a-matrix/assets/144979377/ffc847d8-feac-445b-b568-051dba70d60f)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
