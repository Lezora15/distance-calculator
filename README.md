# distance-calculator

import math
#Ask user for two ordered pairs
x1=int(input("What is your first x?: "))
y1=int(input("What is your first y?: "))
x2=int(input("What is your second x?: "))
y2=int(input("What is your second y?: "))

#Substitute the two ordered pairs
x3= x2-x1
y3= y2-y1 

#Compute
distance=math.sqrt(math.pow(x3, 2) + math.pow(y3, 2))
print("The distance is:", distance)
