# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 1-norm,2-norm and infinity-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
```Python
# Register No: 24900024
# Developed By: JAYANI N

# 1-Norm of a Matrix

	import numpy as np
	A=np.array(eval(input()))
	norm=np.linalg.norm(A,ord=1)
	print(f"{norm:.2f}")


# 2-Norm of a Matrix

	import numpy as np
	A=np.array(eval(input()))
	norm=np.linalg.norm(A,ord=2)
	print(f"{norm:.2f}")


# Infinity Norm of a Matrix

	import numpy as np
	A=np.array(eval(input()))
	norm=np.linalg.norm(A,ord=np.inf)
	print(f"{norm:.2f}")



```
## Output:

### 1-Norm of a Matrix
![alt text](<Screenshot 2024-11-30 114650.png>)

### 2-Norm of a Matrix
![alt text](<Screenshot 2024-11-30 114700.png>)

### Infinity Norm of a Matrix
![alt text](<Screenshot 2024-11-30 114706.png>)

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
