a=int(input("Enter a value:"))
b=int(input("Enter b value:"))
c=int(input("Enter c value:"))
if(not(a>b and a>c)):
    if(b>c):
        print("B is big")
    else:
        print("c is big")
else:
    print("a is big")
