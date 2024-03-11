# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
Step1 :
import numpy as np

Step 2:
arrange the given matrix in np.array command

Step 3: Using the np.linalg.eig(), we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
Step 4:
run the program and get the output

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Sana Fathima H
#RegisterNumber: 212223240145
import numpy as np
A=np.array([[2,-3,0],[2,-5,0],[0,0,3]])
values,vectors=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(values,vectors))
```
## Output:

![image](https://github.com/Sanafathima95773/EIGENVALUES-AND-EIGENVECTORS/assets/147084627/d685da39-deaa-4aef-afcb-c44a0c92660b)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
