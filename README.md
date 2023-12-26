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
# Register No: Harrish Venkat V
# Developed By: 23013973
# 1-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



# 2-Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Infinity Norm of a Matrix

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)



```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/HarrishVenkat/Norm-of-a-matrix/assets/144979588/d3ea7800-5d12-4c05-966d-5654c3a6d5dd)


### 2-Norm of a Matrix
![image](https://github.com/HarrishVenkat/Norm-of-a-matrix/assets/144979588/b25b607c-dc6f-4fd3-9116-9fbdd9db6122)


### Infinity Norm of a Matrix
![image](https://github.com/HarrishVenkat/Norm-of-a-matrix/assets/144979588/39033cac-81b7-4b49-b45b-c3cdfadcc947)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
