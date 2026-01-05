num1 = float(input("write the first number :" ))
uuu =  (input("write the process you wont to generat (+,-,*,/,%) :" ))
num2 = float(input("wirte the sec number : "))

if uuu == "+":
    result = num1 + num2
    print(num1,"+",num2,"=", result)
elif uuu== "-" :
    result = num1- num2
    print(num1,"-",num2,"=",result)
elif uuu== "*" :
    result= num1 * num2
    print(num1,"*",num2,"=",result)
elif uuu== "/" :
    if num2 == 0 :
        print("this is imposible process")
    elif num2 != 0 :
        result= num1/num2
        print(num1,"/",num2,"=",result)
elif uuu== "%" :
    result = num1 % num2
    print(num1,"%",num2,"=",result)
else:
    print("Erorr please enter a right process and try agin ")
