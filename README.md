# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
Start the program
### Step 2:
Import the numpy module to use the built-in functions for calculation 
### Step 3: 
Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4
End program 

## Program:
```
#Program to find the eigen values and eigen vectors.
#Developed by:DHARANISH MS 
#RegisterNumber:23011819
import numpy as np
a= np.array([[-2,2,-3],[2,1,-6],[-1,-2,0]])
values,vectors = np.linalg.eig(a)
print("Eigen values are",values,"and Eigen Vectors are",vectors) 
```
## Output:

![image](https://github.com/MSDharanish-23011819/EIGENVALUES-AND-EIGENVECTORS/assets/147139454/85bd42bb-bd6b-4cb4-9f50-dfa84808cce9)

## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
