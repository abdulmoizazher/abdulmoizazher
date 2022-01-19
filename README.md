import cmath

a=float(input("enter a"))
b=float(input("enter b"))
c=float(input("enter c"))
if (b*b-4*a*c)==0:
    print("solution is not possible")
else:
    import cmath
    print("first value of a",(b+cmath.sqrt(b*b-4*a*c))/2*a)
    print("first value of a",(b-cmath.sqrt(b*b-4*a*c))/2*a)
