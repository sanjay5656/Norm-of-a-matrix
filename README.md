# Norm of a matrix :
## Aim :
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required :
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm :
1. Get the input matrix using np.array()
2. Find the 2-norm of the matrix using np.linalg.norm()
3. Print the norm of the matrix in two decimal places.
## Program :
Register No : 212221243002 
Developed By: Sanjay S
## 1-Norm of a Matrix :
```python
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,1)
norm="{:.2f}".format(ans)
print(norm)
```
## 2-Norm of a Matrix :
```python
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,2)
norm="{:.2f}".format(ans)
print(norm)
```
## Infinity Norm of a Matrix :
```python
import numpy as np
a=np.array(eval(input()))
ans=np.linalg.norm(a,np.inf)
norm="{:.2f}".format(ans)
print(norm)
```
## Output :
### 1-Norm of a Matrix :
![image](https://github.com/sanjay5656/Norm-of-a-matrix/assets/115128955/066cd875-b7cb-4e3d-a35e-ec0d81f9ee64)

### 2-Norm of a Matrix :
![image](https://github.com/sanjay5656/Norm-of-a-matrix/assets/115128955/b1250a34-f898-4bef-8b45-144944309216)

### Infinity Norm of a Matrix :
![image](https://github.com/sanjay5656/Norm-of-a-matrix/assets/115128955/91eab785-c6a4-4e15-991a-72c1edddb699)

## Result :
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
