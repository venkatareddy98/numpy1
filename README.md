# numpy1
# numpy program 1:
import numpy as np

a=np. array([1, 2, 3, 4, 5]) 
print(a)

b = np.array([[1, 2, 3], [4, 5, 6] ]) 
print(b)

c = np.zeros((3, 4))
print(c) 

d = np.ones((2, 2))
print(d)
 
Output:

[1 2 3 4 5]
[[1 2 3]
 [4 5 6]]
[[0. 0. 0. 0.]
 [0. 0. 0. 0.]
 [0. 0. 0. 0.]]
[[1. 1.]
 [1. 1.]]

# numpy program 2:

a=np.array([1, 2, 3])

b=np.array([4, 5, 6])

c = a + b

print(c)

d=np.array([[1, 2], [3, 4]])

e=np.array([[5, 6], [7, 8]])
f = d * e

print(f)

g=np.array([[1, 2], [3, 4]]) 
h=np.array([[5, 6], [7, 8]])

i=np.dot (g, h)s
print(i)

Output:

[5 7 9]
[[ 5 12]
 [21 32]]
[[19 22]
 [43 50]]
