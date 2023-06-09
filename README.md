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
get input as a=np.array(eval(input()))
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 
print the eigenvectors and eigen values by the print statement
## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by: Surya S K
#RegisterNumber:212222100052
import numpy as np
A=np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
evalues,evector=np.linalg.eig(A)
print("Eigen values are {} and Eigen Vectors are {}".format(evalues,evector))
```

## Output:
![Screenshot 2023-06-10 023913](https://github.com/SuryaSK46/EIGENVALUES-AND-EIGENVECTORS/assets/127716537/a4e937a6-d4df-415a-974f-a88d3fd55952)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
