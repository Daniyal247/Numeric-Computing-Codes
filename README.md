#Bisection Method in Numeric Computing
def f(x):
    return x**3-4*x-9
def bisectionmethod(x0, x1):
    for i in range(9):
        midpoint = (x0 + x1)/2
        if(f(midpoint) < 0):
            x0 = midpoint
            print(str(i+1) + " change in x0", x0)
        else:
            x1 = midpoint
            print(str(i+1) + " change in x1", x1)
x0 = 2
x1 = 3
bisectionmethod(x0, x1)

#Code written by Syed Danial Khurram
