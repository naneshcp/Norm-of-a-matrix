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
# Register No:Naneshvaran C
# Developed By:212224110038
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
<br>
<br>
<br>
![Screenshot 2025-05-20 221345](https://github.com/user-attachments/assets/e9cda0af-4d4c-4f23-a226-3b51f7e0ba67)

### 2-Norm of a Matrix
<br>
<br>
<br>
![Screenshot 2025-05-20 221354](https://github.com/user-attachments/assets/0e599dae-3d02-4a71-8476-926bfaa601fa)

### Infinity Norm of a Matrix
<br>
<br>
<br>![Screenshot 2025-05-20 221401](https://github.com/user-attachments/assets/dd0f7416-cd43-43ed-8042-ee60f8fa50a6)


## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
