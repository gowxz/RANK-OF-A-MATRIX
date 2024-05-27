# Ex:2.RANK-OF-A-MATRIX

# Date:23/03/2024

## Aim:
To write a python program to find the rank of a matrix

## Equipment’s required:
1. 	Hardware – PCs
2. 	Anaconda – Python 3.7 Installation / Moodle-Code Runner
   
## Algorithm:

## Step 1: 
   importing the NumPy library using the statement import numpy as np.
## Step 2: 
   Define a 3x3 matrix A with the specified values.
## Step 3: 
   Compute the rank of matrix A using the np.linalg.matrix_rank() function.
## Step 5: 
   Display the rank of matrix A using the print() statement.
## Step 4: 
   End the program.
   



## QUESTION:
```
Write a program to find the rank for the given matrix([5,-3,-10],[2,2,-3],[-3,-1,5]).
```
## Program:
```
Developed by:Gowtham S 
RegisterNumber:2305002008  

```
`````python
import numpy as np
A=np.array([[5,-3,-10],[2,2,-3],[-3,-1,5]])
rank=np.linalg.matrix_rank(A)
print(rank)
`````

## Output:
![Screenshot 2024-04-08 100337](https://github.com/gowxz/RANK-OF-A-MATRIX/assets/155504997/78d132b8-8bed-499c-8499-35a96170accc)



## Result:
Thus the rank for the given matrix is successfully solved by  using a python program.
