# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in function for calculation.
### Step 2: 
Prepare the lists from each linear equations and assign in np.array().
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the solution.
### Step 4: 
End the program.
## Program:
```python
#Program to find the rank of a matrix.
#Developed by: Aravind Kumar. S. S
#RegisterNumber:23004721

import numpy as np
a=np.array([[3,2,5],[1,1,2],[3,3,6]])
b=np.linalg.matrix_rank(a)
print(b)

```
## Output:
![Screenshot 2023-12-17 225008](https://github.com/aravindkumar23004721/RANK-OF-A-MATRIX/assets/148962674/89ab0e86-55d9-413e-aa57-e951e3cd5795)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

