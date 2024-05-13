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
#Developed by: your name : Adhithya K
#RegisterNumber: 2305002001

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
![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/8e4fd6a9-6314-4d55-84be-4a5f1bd6cf7e)



### 2-Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/b3f828ff-f1b7-4d4e-ab0f-d4bf2408f136)

### Infinity Norm of a Matrix
![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/357397d1-3143-47ad-90e1-156371dd397d)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
