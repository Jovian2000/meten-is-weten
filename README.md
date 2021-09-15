# meten-is-weten
## input en if-statement
a = int(input("a = "))
b = int(input("b = "))
if a > b: 
    Max = a
    Min = b
    print("a is het grootste getal: " + str(Max))
## elif-statement
a = int(input("a = "))
b = int(input("b = "))
if a > b: 
    Max = a
    Min = b
    print("a is het grootste getal: " + str(Max))
elif a < b:
    Max = b
    Min = a
    print("a is het kleinste getal: " + str(Min))
## else-statement
a = int(input("a = "))
b = int(input("b = "))
if a > b: 
    Max = a
    Min = b
    print("a is het grootste getal: " + str(Max))
elif a < b:
    Max = b
    Min = a
    print("a is het kleinste getal: " + str(Min))
else:
    print("a en b zijn even groot")
## Min en Max
a = int(input("a = "))
b = int(input("b = "))
if a > b: 
    Max = a
    Min = b
    print("a is het grootste getal: " + str(Max))
    print("Het maximum is: " + str(Max))
    print("Het minimum is: " + str(Min))

elif a < b:
    Max = b
    Min = a
    print("a is het kleinste getal: " + str(Min))
    print("Het maximum is: " + str(Max))
    print("Het minimum is: " + str(Min))
else:
    Max = a
    Max = b
    print("a en b zijn even groot")
    print("Het maximum is: " + str(Max))
    print("Het minimum is: " + str(Min))