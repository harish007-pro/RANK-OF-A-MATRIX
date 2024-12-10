# RANK-OF-A-MATRIX
## Aim:
To write a python program to find the rank of a matrix
## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step 1:  import numpy as np
### Step 2:  Define the matrix
### Step 3: Using the np.linalg.matrix_rank(), we can find the rank of the given matrix.
### Step 4: print(rank)
## Program:
    # Program to find the rank of a matrix.
    # Developed by: Harish G
    # RegisterNumber:24006523
    import numpy as np

    # Define the matrix
    matrix = np.array([[1, 2, 3],
                    [3, 6, 9]])

    # Calculate the rank of the matrix
    rank = np.linalg.matrix_rank(matrix)

    # Print the rank
    print(rank)

## Output:
![result](<Screenshot 2024-12-10 082149.png>)
## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.

