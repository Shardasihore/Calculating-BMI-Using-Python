# Calculating-BMI-Using-Python

h = float(input("enter your height"))
H = h*0.305
W = int(input('enter your weight'))

BMI = W/H**2

if BMI < 18.5:
    print("you are underweight and your BMI is :",BMI)
elif BMI >=18.5 and BMI <24.9:
    print("you are normal and your BMI is :",BMI)
elif BMI >=25 and BMI<29.9:
    print("you are overweight and your BMI is :",BMI)
elif BMI >= 30:
    print("you are obessed and your BMI is :",BMI)

