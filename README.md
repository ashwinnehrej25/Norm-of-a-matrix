# Norm of a matrix
## Aim
To write a program to find the 1-norm, 2-norm and infinity norm of the matrix and display the result in two decimal places.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
	1. Get the input matrix using np.array()   
    2. Find the 2-norm of the matrix using np.linalg.norm()
	3. Print the norm of the matrix in two decimal places.
## Program:
Program to find 2-norm of a matrix.
```
Developed by: K.Ashwin Nehrej
RegisterNumber: 212225220014
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

one_norm = np.linalg.norm(A, 1)

print(f"{one_norm:.2f}")
```

Program to find 2-norm of a matrix.
```
Developed by:K.Ashwin Nehrej
RegisterNumber: 212225220014
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
import numpy as np

A = np.array(eval(input()))

l2_norm = np.linalg.norm(A, 2)
<img width="1277" height="378" alt="593691048-b440435a-3ca7-46d9-af92-a959f14970aa" src="https://github.com/user-attachments/assets/24aaf61b-989d-4cc7-b354-ef9f85877781" />
<img width="1277" height="378" alt="593691048-b440435a-3ca7-46d9-af92-a959f14970aa" src="https://github.com/user-attachments/assets/bb946a52-3e05-41cf-a6ad-90fe09f52bd0" />

print(f"{l2_norm:.2f}")

```
# Infinity Norm of a Matrix
```
Program to find 2-norm of a matrix.
Developed by:K.Ashwin Nehrej
RegisterNumber: 212225220014
import os
os.environ["OPENBLAS_NUM_THREADS"]="1"
A = eval(input())

max_sum = 0

for row in A:
    row_sum = sum(abs(x) for x in row)
    if row_sum > max_sum:
        max_sum = row_sum

print(f"{max_sum:.2f}")

```
## Output:
### 1-Norm of a Matrix
<img width="1277" height="378" alt="image" src="https://github.com/user-attachments/assets/89a48508-9046-4ff3-b116-b13b1b01f878" />


### 2-Norm of a Matrix
<img width="1308" height="459" alt="image" src="https://github.com/user-attachments/assets/07758042-3ba1-4b79-a2fc-dbd0d1edab13" />


### Infinity Norm of a Matrix

<img width="1285" height="369" alt="image" src="https://github.com/user-attachments/assets/f7f4e931-901c-43df-a1f6-be5308b8e468" />

## Result
Thus the program for 1-norm, 2-norm and Infinity norm of a matrix are written and verified.
