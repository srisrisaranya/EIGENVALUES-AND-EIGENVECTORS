# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 : 
### Step 2: 
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.
### Step 4: 

## Program:
```
#Developed by: saranya S
#RegisterNumber:23013399

import numpy as np
a=np.array([[4,2],
            [2,4]])
Values,Vectors=np.linalg.eig(a)
print("Eigen values are {} and Eigen Vectors are {}".format(Values,Vectors))
```

## Output:
![image](https://github.com/srisrisaranya/EIGENVALUES-AND-EIGENVECTORS/assets/148516638/7149e838-2cff-4b08-a77b-9b4bf8e21bf8)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
