# Simple-calculator-Using-Function
#Find Simple calculator online for math with addition, subtraction, division and multiplication. Only Two Values
def add(a,b):
    return a+b;
def sub(a,b):
    return a-b;
def multiplx(a,b):
    return a*b;
def div(a,b):
    return a/b;
while True:
    print("Select Opestion(+,-,*,/)")
    num1=int(input("Enter First Number:- "))
    num2=int(input("Enter Second NUmber:- "))
    a=input("Select Opestion(+,-,*,/,Quit==3")
    if(a=="+"):
        print(add(num1,num2))
    elif(a=="-"):
        print(sub(num1,num2))
    elif(a=="*"):
        print(multiplx(num1,num2))
    elif(a=='/'):
        print(div(num1,num2))
    elif(a=="3"):
        print("Quit This Program")
        break;
    else:
        print("Sorry Defult Values")


