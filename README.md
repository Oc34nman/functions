# functions

def findsmallest(x, y, z):
    if(x > y & x > z):
        print(x, "is the biggest of the three (or x)")
    elif(y > x & y > z):
        print(y, "is the biggest of the three (or x)")
    else:
        print(z, "is the biggest of the three (or z)")
    return
result = findsmallest(5, 4, 2)
   
