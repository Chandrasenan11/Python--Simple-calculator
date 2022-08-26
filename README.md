# Python--Simple-calculator
x = float(input('enter the number: '))
y = float(input('enter the number: '))
print('main menu')
print('1. ADD')
print('2. SUB')
print('3. PRO')
print('4. DIV')
ch = float (input("Enter the choice: "))
if ch == 1 :
    Sum = x+y
    print("Sum=", Sum)
elif ch==2:
    sub= x-y
    print("sub=", sub)
elif ch==3:
    pro= x*y
    print("pro=", pro)
elif ch==4:
    div= x/y
    print("div=", div)
else:
    print ("error")
