# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:
Import the numpy module to use the built-in functions for calculation
### Step 2:
Prepare the lists from each equation and assign in np.array
### Step 3: 
Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4:
end the program
## Program:
```python
#Program to find the eigen values and eigen vectors.
#Developed by: SANJAY M
#RegisterNumber: 212222110038

import numpy as np
A = np.array([[1, 2, 3],
              [3, 6, 9]])
rank = np.linalg.matrix_rank(A)
print("", rank)

```
## Output:
![Screenshot 2025-04-26 104139](https://github.com/user-attachments/assets/07bfe219-593d-4517-b315-c8b78a2cda72)

## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

