# calculator mini project
def add(a,b):
    return(a + b)
    
def multiply(a,b):
    return(a * b)
    
def division(a,b):
    return(a / b)
    
def minus(a,b):
    return(a - b)

firstnum = int(input("Enter no.:"))
secondnum = int(input("Enter no.:"))

print("1.add")
print("2.multiply")
print("3.division")
print("4.minus")

choice = int(input("Enter no.:"))

if choice == 1:
    print(add(firstnum , secondnum))
elif choice == 2:
    print(multiply(firstnum , secondnum))
elif choice == 3:
    print(division(firstnum , secondnum))
elif choice == 4:
    print(minus(firstnum , secondnum))
else:
    print("invalid choice")
