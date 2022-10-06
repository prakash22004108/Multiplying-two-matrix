# Multiplying-two-matrix

## AIM:

## ALGORITHM:

### Step 1:
Import numpy as np.

### Step 2:
Create a empty list.

### Step 3:
Using for loops append the two lists.

### Step 4:
Assign the arrays.

### Step 5:
Display the result.

## PROGRAM: 
```
# To write a python program for Multiplying two matrices.
# Developed by : PRAKASH R
# Register Number : 22004108


import numpy as np
l1,l2=[],[]
n= int(input())
for i in range(n):
    l1.append(int(input()))
for i in range(n):
    l2.append(int(input()))
value1=np.array(l1)
value2=np.array(l2)
result=value1*value2
print("Product of two arrays is:",result)
```

## OUTPUT:
![output](/OP.png)

## RESULT:
Python program for multiplying two matrices is successful.

