# Calculator-

print("Enter 1 for ADDITION")
print("Enter 2 for SUBTRACTION")
print("Enter 3 for MULTIPLICATION")
print("Enter 4 for DIVISION")
print("---------------------------------------------------")
operation = int(input("Select operation from 1-4:"))
a= int(input("Enter first number:"))
b= int(input("Enter second number:"))
if operation == 1:
	print("The sum is:", (a+b))
elif operation == 2:
	print("The difference is:", (a-b))
elif operation == 3:
	print("The product is:", (a*b))
elif operation == 4:
	print("The quotient is:", (a/b))
else:
	print("Invalid Operation")

#create a python program that will allow the user to choose;"
#from the ff. choices as menu.;"
# 1. Addtion;"
# 2. Subtraction;"
# 3. Multiplication;"
# 4. Division
