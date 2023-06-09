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
# Register No: 212222230051
# Developed By:JANARTHANAN V K

# 1-Norm of a Matrix
'''
Program to find 1-norm of a matrix.
Developed by: JANARTHANAN V K
Register number: 212222230051
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,1)
norm="{:.2f}".format(soln)
print(norm)



# 2-Norm of a Matrix

'''
Program to find 2-norm of a matrix.
Developed by: JANARTHANAN V K
Register number: 212222230051
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,2)
norm="{:.2f}".format(soln)
print(norm)


# Infinity Norm of a Matrix

'''
Program to find infinity-norm of a matrix.
Developed by: JANARTHANAN V K
Register number: 212222230051
'''
import numpy as np
a=np.array(eval(input()))
soln=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(soln)
print(norm)



```
## Output:
### 1-Norm of a Matrix
![Screenshot 2023-06-09 200522](https://github.com/Janarthanan2/Norm-of-a-matrix/assets/119393515/72f21fb7-2bf8-4ab5-b287-2de8bb9effa0)

<br>

### 2-Norm of a Matrix
![Screenshot 2023-06-09 200621](https://github.com/Janarthanan2/Norm-of-a-matrix/assets/119393515/22f9f10c-4a2b-4c64-a615-2ee3811c3ac3)

<br>

### Infinity Norm of a Matrix
![Screenshot 2023-06-09 200733](https://github.com/Janarthanan2/Norm-of-a-matrix/assets/119393515/b8c17235-eb35-4d70-8ffe-2c8544cf0a39)

<br>
<br>

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
