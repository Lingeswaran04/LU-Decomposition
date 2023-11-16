# LU Decomposition 

## AIM:
To write a program to find the LU Decomposition of a matrix.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1.Import the numpy module to use the built-in functions for calculation.

2.From scipy.linalg module import the lu funtion.

3.Get inputs from the user and assign the values in np.array().

4.Using the lu() function,we can find the L and U matrix.

5.Print the obtained values.

6.End the program.

## Program:
(i) To find the L and U matrix
```
/*
'''Program to find L and U matrix using LU decomposition.
Developed by: LINGESWARAN.K
RegisterNumber: 212222110022
'''
import numpy as np 
from scipy.linalg import lu
a=eval(input())
P,L,U=lu(a)
print(L)
print(U)
*/
```
(ii) To find the LU Decomposition of a matrix
```

/*
'''Program to find L and U matrix using LU decomposition.
Developed by: LINGESWARAN.K
RegisterNumber: 212222110022
'''
#To print X matrix (solution to the equations)
import numpy as np
from scipy.linalg import lu_factor,lu_solve
A=eval(input())
B=eval(input())
lu,piv=lu_factor(A)
x=lu_solve((lu,piv),B)
print(x)
*/

```

## Output:
![lu decomposition]()
(i) To find the L and U matrix
![Screenshot 2023-11-16 202919](https://github.com/Lingeswaran04/LU-Decomposition/assets/119103865/6996fff8-49e7-43be-99a0-92ee626d2317)


(ii) To find the LU Decomposition of a matrix

![image](https://github.com/Lingeswaran04/LU-Decomposition/assets/119103865/6a9de95a-6858-4c6e-9393-29145156de74)



## Result:
Thus the program to find the LU Decomposition of a matrix is written and verified using python programming.

