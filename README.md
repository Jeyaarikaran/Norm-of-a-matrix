# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
  1 norm of matrix:
  ```
	1. Get the input matrix using np.array()   
        2. Find the 1-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
````
2 norm of matrix:
```
       	1. Get the input matrix using np.array()   
        2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
inf norm of matrix:
```
 	1. Get the input matrix using np.array()   
        2. Find the inf-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
```
## Program:
```Python
# Register No:24002171
# Developed By:jeyaarikaran P
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
	inform="{:.2f}".format(ans)
	print(inform)



```
## Output:
### 1-Norm of a Matrix
![image 1](<Screenshot 2024-12-01 201445.png>)

### 2-Norm of a Matrix
 ![image 2](<Screenshot 2024-12-01 201516.png>)

### Infinity Norm of a Matrix
![image3](<Screenshot 2024-12-01 201529.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
