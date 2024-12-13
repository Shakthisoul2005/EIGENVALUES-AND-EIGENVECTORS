# EIGENVALUES-AND-EIGENVECTORS
## Aim:
To write a python program to find the Eigenvalues and Eigen Vectors
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1 :
import numpy module to use the built functions for calculation
### Step 2:
prepare the lists from each linear equationa and assign in np.array()
### Step 3: Using the np.linalg.eig(),  we get two results (first is eigenvalue and second is eigenvector) of the given matrix.

### Step 4:
end the program

## Program:
    import numpy as np
    matrix=np.array([[4,2],[2,4]])
    e_values,e_vectors=np.linalg.eig(matrix)
    print("Eigen values are {} and Eigen Vectors are {}".format(e_values,e_vectors ))

## Output:
![image 1](<Screenshot 2024-11-18 162327.png>)
## Result:
Thus the Eigenvalue and Eigenvector is successfully solved using python program
