# Codsoft-internship-

task 1 simple calcuator .


num1 = float(input("enter 1st number :"))
num2 = float(input("enter 2nd number : "))
print("press 1 for addition \n press 2 for subtraction \n press 3 for division \n press 4 for multiplication")
choice = int(input("choose 1/2/3/4 :  "))
if choice == 1:
    print(num1 + num2)
elif choice == 2:
    print(num1 - num2)
elif choice == 3:
    print(num1 / num2)
elif choice == 4:
    print(num1 * num2)
else :
    print("Invalid input")
