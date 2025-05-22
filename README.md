# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1: import the numpy function
### Step 2: get the input as array
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: then we print the output
## Program:
```
import numpy as np

matrix = np.array([[3, 2, 5],
                   [1, 1, 2],
                   [3, 3, 6]])

rank = np.linalg.matrix_rank(matrix)

print(f"{rank}")
```
## Output:
![image](https://github.com/user-attachments/assets/7dd0cad9-1102-4fec-912a-ac52a1f24ba2)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

