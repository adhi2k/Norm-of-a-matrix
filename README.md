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
#Developed by: your name : VasanthKumar V
#RegisterNumber: 2305002027

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
![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/705bfdd3-ad14-4dfb-9dfd-7087cbf73f92)



### 2-Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/4ce65c2f-0649-4ab2-b37c-32155d747937)

### Infinity Norm of a Matrix

![image](https://github.com/adhi2k/Norm-of-a-matrix/assets/145216997/8b2cb4e5-1bed-4976-94d8-4f774b4ca488)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
