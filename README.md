# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy as np
### Step 2:
take input from user.
### Step 3:
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print output.
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: YUVARAJ B
#RegisterNumber:212222230182
import numpy as np
A=np.array([[2,2],[1,3]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {0} and Eigen Vectors are {1}".format(evalues,evector))
```

## Output:
![image](https://user-images.githubusercontent.com/118343998/226292515-bb808778-05a7-4d8e-8963-ed3254624cc7.png)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
