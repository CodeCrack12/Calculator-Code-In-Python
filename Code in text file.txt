from math import *

print("Select Operation : ")
a, b, c, d, e, f, g, h, i, j = "Addition", "Subtraction", "Division", "Multiplication", "Floor Division", "Exponent", "Modulus", "Absolute", "Ceil", "Floor"
print(
    "1. " + a + "\n" + "2. " + b + "\n" + "3. " + c + "\n" + "4. " + d + "\n" + "5. " + e + "\n" + "6. " + f + "\n" + "7. " + g + "\n" + "8. " + h + "\n" + "9. " + i + "\n" + "10. " + j)

operation = int(input("Operation = "))
if operation == 1 or operation == 2 or operation == 3 or operation == 4 or operation == 5 or operation == 6 or operation == 7:
    print("Enter Any 2 Numbers : ")
    n1 = int(input("Enter 1st Number : "))
    n2 = int(input("Enter 2nd Number : "))
    if operation == 1:
        print("Addition of these 2 numbers is : " + str(n1 + n2))
    elif operation == 2:
        print("Subtraction of these 2 numbers is : " + str(n1 - n2))
    elif operation == 3:
        print("Division of these 2 numbers is : " + str(n1 / n2))
    elif operation == 4:
        print("Multiplication of these 2 numbers is : " + str(n1 * n2))
    elif operation == 5:
        print("Floor Division of these 2 numbers is : " + str(n1 // n2))
    elif operation == 6:
        print("Exponent of 1st number power 2nd number is : " + str(n1 ** n2))
    elif operation == 7:
        print("Modulus of these 2 numbers is : " + str(n1 % n2))

elif operation == 8 or operation == 9 or operation == 10:

    number = float(input("Enter any number : "))
    if operation == 8:
        print("Absolute of the number is : " + str(abs(number)))
    elif operation == 9:
        print("Ceil of the number is : " + str(ceil(number)))
    elif operation == 10:
        print("Floor of the number is : " + str(floor(number)))
else:
    print("Error.")
input("Press Enter To Exit")
