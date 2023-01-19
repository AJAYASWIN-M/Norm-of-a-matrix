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
![Screenshot (138)](https://user-images.githubusercontent.com/118679692/213352030-5d50fdaa-54fa-45bf-923b-69d436effe40.png)
<br>
<br>
<br>

### 2-Norm of a Matrix
![Screenshot (139)](https://user-images.githubusercontent.com/118679692/213352050-c3b88431-d9f3-4c5d-bbbc-82d144eccc30.png)
<br>
<br>
<br>

### Infinity Norm of a Matrix
![Screenshot (140)](https://user-images.githubusercontent.com/118679692/213352277-8668bcdf-4207-49fb-8d58-eb912f51b0d7.png)

<br>
<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
