What is Vector? 

* Vetor is a list of numbers which we can visualize it in space.

![image](https://user-images.githubusercontent.com/42385240/192158684-2ee676b8-4b24-4fe8-ae30-9e66719b80df.png)

* Vector has magnitude and direction.

![image](https://user-images.githubusercontent.com/42385240/192158323-c6158aa9-5087-4a1e-aa18-a766c28f18f8.png)

* Vecor can start from any point in the plane. 
* Vector can be notated like these below ways: 
        Using an arrow : -> 
        Using boldface : V
        
 * Vector represent in one column is referred to as column vector 
 Ex: ![image](https://user-images.githubusercontent.com/42385240/192159595-e91d747f-0078-4d22-9100-02a4f914c635.png)
 
 In Python numpy
# 2-dimensional vector
v2 = [7,-2]
v2=np.array([v2])
v2.T

![image](https://user-images.githubusercontent.com/42385240/192160534-f7f61114-68e3-41ff-b6ef-69c36b9abf83.png)

* Vector represent in one row is referred to as row vector. 
![image](https://user-images.githubusercontent.com/42385240/192159628-efc686ba-60d3-46fe-95f6-75845551fdc8.png)

# 3-dimensional vector'
v3 = [4,8,9]
v3 = np.array(v3)
v3

In python numpy:  
![image](https://user-images.githubusercontent.com/42385240/192160666-3305f7a4-36a6-42ad-a583-5e3a9337dbe3.png)

To plot the two and three dimentional vector . Below is the price of code: 
'''
import numpy as np
import matplotlib.pyplot as plt
from mpl_toolkits.mplot3d import Axes3D

v2 = [ 5, 2 ]

# 3-dimensional vector
v3 = [ 3, -1, 2 ]

# row to column (or vice-versa):
v3t = np.transpose(v3)


# plot them
plt.plot([0,v2[0]],[0,v2[1]])
plt.axis('equal')
plt.plot([-6, 6],[0, 0],'k--')
plt.plot([0, 0],[-6, 6],'k--')
plt.grid()
plt.axis((-4, 4, -4, 4))
plt.show()

fig = plt.figure(figsize=plt.figaspect(1))
ax = plt.axes(None, projection='3d')
ax.plot([0, v3[0]],[0, v3[1]],[0, v3[2]],linewidth=3)

# make the plot look nicer
ax.plot([0, 0],[0, 0],[-4, 4],'k--')
ax.plot([0, 0],[-4, 4],[0, 0],'k--')
ax.plot([-4, 4],[0, 0],[0, 0],'k--')
plt.show()
'''

![image](https://user-images.githubusercontent.com/42385240/192196823-562d4019-a090-4756-ae60-3c124a49f564.png)
![image](https://user-images.githubusercontent.com/42385240/192197146-d31a752c-8b54-40eb-aff9-e0410f25af71.png)


        



