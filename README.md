# Inverse-of-matrix

AIM:To find Inverse-of-matriV

ALGORITHM:
Step 1:import numpy as np
Step 2:create an empty lists
Step 3:get inputs from the user
Step 4:use inverse function
Step 5:run the program

## PROGRAM:
~~~
import numpy as np
l1,l2 = [],[]
r,c= int(input()),int(input())
for i in range(r):
    for j in range(c):
        num=int(input ())
        l1.append (num)
    l2. append (l1)
    l1=[]
print (l2)
valuel=np.array(l2)
inverse = np.linalg.inv(valuel)
print (inverse)

## OUTPUT:
~~~
<img width="527" alt="MEKK" src="https://user-images.githubusercontent.com/94882905/154801579-40f1dd08-1cbb-47f6-8900-7bd665afaafa.png">


## RESULT
Thus,the program is excuted.
