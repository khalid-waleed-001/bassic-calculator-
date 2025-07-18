# bassic-calculator-
#Just for Sum Multiplication Subtraction or Division


 num = int(input("Enter your first number:"))
num2 = int(input("Enter your second number:"))

 print('\nChoose your choice')
 print("1. Addition")
 print("2. Subtraction")
 print("3. Multiplication")
 print("4. Division")

 choice = input("Enter choice from(1-4) ")
 if choice == '1':
     print(num+num2)
 elif choice == '2':
     print(num-num2)
 elif choice == '3':
     print(num*num2)
 elif choice == '4':
    print(num/num2)
 else:
     print('invalid choice')
