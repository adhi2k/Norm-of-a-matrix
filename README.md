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
#Developed by: your name : Sri Muthazhagan P
#RegisterNumber: 2305002024

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
![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/d02fbfda-fe82-408e-83f0-eb048dd186fe)



### 2-Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/a34d374f-8fe9-4148-af32-d141a5d3122f)

### Infinity Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/e6373e8a-0f55-401d-856a-c7f664038fa6)



## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
