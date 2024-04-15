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

# 1-Norm of a Matrix
```
Program to find 1-norm of a matrix.
Developed by: KATHIRESAN K
RegisterNumber: 212223110021
```
```
import numpy as np
matrix=eval(input())
one_matrix=np.linalg.norm(matrix,1)
print("{:.2f}".format(one_matrix))
```
# 2-Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by: KATHIRESAN K
RegisterNumber: 212223110021
```
```
import numpy as np
matrix=eval(input())
two_matrix=np.linalg.norm(matrix,2)
print("{:.2f}".format(two_matrix))
```
# Infinity Norm of a Matrix
```
Program to find infinity norm of a matrix.
Developed by: KATHIRESAN K
RegisterNumber: 212223110021
```
```
import numpy as np
matrix=eval(input())
#two_matrix=np.linalg.norm(matrix,2)
one_matrix=np.linalg.norm(matrix,1)
infinity_matrix=np.linalg.norm(matrix,np.inf)
print(format(infinity_matrix))
```
## Output:
### 1-Norm of a Matrix
![Screenshot 2024-04-14 175720](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/a702016c-ae42-4135-a2d6-eab3684ff46a)

![image](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/7ba25f9e-291f-4481-8f70-0f3f81af2c25)

### 2-Norm of a Matrix
![image](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/e716be02-7f83-493c-9bf8-c6917e824146)

![image](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/8db57f43-3054-42f4-a173-c39ada26bdd3)


### Infinity Norm of a Matrix
![image](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/fd4916a4-fb26-467b-b1c4-df23571b8d94)

![image](https://github.com/Kathiresan-23013376/Norm-of-a-matrix/assets/150008375/55933efc-a79d-4f7f-8c9f-e9cfb842b6e9)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
