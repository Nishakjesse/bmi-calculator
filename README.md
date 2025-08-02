# bmi-calculator
basically calculates one"s BMI and gives interpretation
print("welcome to the bmi calculator")
weight =float(input("what is your weight in kg"))
height =float(input("what is your height in meters"))
square_root_of_heigt= float(height * height)
BMI = weight/square_root_of_heigt
if BMI >=30:
 print("you are obese")
elif BMI >=25:
  print("your are overweight")
elif BMI>=18.5:
  print("normal weight")
else:
  print("you are underweight")
