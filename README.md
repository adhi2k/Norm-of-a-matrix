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
#Developed by: your name : Harish Gowtham E
#RegisterNumber: 2305002009

# 1-Norm of a Matrix
import numpy as np
mat = np.array(eval(input()))
ans = np.linalg.norm(mat,1)
Norm_of_matrix = "{:.2f}".format(ans)
print(Norm_of_matrix)

# 2-Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)


# Infinity Norm of a Matrix
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
Norm_of_matrix="{:.2f}".format(ans)
print(Norm_of_matrix)

```
## Output:
### 1-Norm of a Matrix
![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/bcb86fcf-a2be-4f2e-8661-fbdd94aa00b2)



### 2-Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/a3f79a99-cf44-41af-b96f-52e40fa62ad7)

### Infinity Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/8d6896b8-410e-4c5c-a5ce-c649144d8d76)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
