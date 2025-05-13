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
# Register No:
# Developed By:
# 1-Norm of a Matrix

'''
program to find 1-Norm of a matrix.
Developed by:VENKATA MOHAN N.
Register number:212224230298
'''

import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,1)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)


# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: VENKATA MOHAN N.
RegisterNumber: 212224230298
'''


import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,2)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)

# Type your code here



# Infinity Norm of a Matrix
'''
Program to find the infinity of a matrix.
Developed by: VENKATA MOHAN N.
RegisterNumber: 212224230298
'''
import numpy as np
mat=np.array(eval(input()))
ans=np.linalg.norm(mat,np.inf)
norm_of_matrix="{:.2f}".format(ans)
print(norm_of_matrix)




```
## Output:
### 1-Norm of a Matrix
<br>
<br>
<br>

![image](https://github.com/user-attachments/assets/5c9b0bb8-77bd-4309-aad0-dae8a8f4811f)




### 2-Norm of a Matrix
<br>
<br>
<br>

![image](https://github.com/user-attachments/assets/d1735338-c02a-42b2-bbf9-28b86e2ab280)


### Infinity Norm of a Matrix
<br>
<br>

<br>

![image](https://github.com/user-attachments/assets/7ffc7a13-9d86-4381-8d6d-ebcbb1bb9e21)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
