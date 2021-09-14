# meten-is-weten
## input en if-statement
a = int(input("a = "))
b = int(input("b = "))

if a > b: 
    Max = a
    print("a is het grootste getal: " + str(Max))
## elif-statement
a = int(input("a = "))
b = int(input("b = "))

if a > b: 
    Max = a
    print("a is het grootste getal: " + str(Max))
elif a < b:
    Min = a
    print("a is het kleinste getal: " + str(Min))
## else-statement
a = int(input("a = "))
b = int(input("b = "))

if a > b: 
    Max = a
    print("a is het grootste getal: " + str(Max))
elif a < b:
    Min = a
    print("a is het kleinste getal: " + str(Min))
else:
    print("a en b zijn even groot")