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
# Register No:23004345
# Developed By:Devesh s
# 1-Norm of a Matrix

import numpy as np

mat=np.array(eval(input()))

ans=np.linalg.norm(mat,1)

Norm_of_matrix="{:.2f}".format(ans)

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
![Screenshot 2023-12-31 133047](https://github.com/23004345/Norm-of-a-matrix/assets/138849203/246e288a-2dbb-4cc0-b5fa-913f2a6f1620)




### 2-Norm of a Matrix
![Screenshot 2023-12-31 133100](https://github.com/23004345/Norm-of-a-matrix/assets/138849203/37369c30-c3c2-45d0-9230-abc17414752a)


### Infinity Norm of a Matrix
![Screenshot 2023-12-31 133112](https://github.com/23004345/Norm-of-a-matrix/assets/138849203/62ab6819-f0fc-4d85-8202-bfd411122dc5)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
