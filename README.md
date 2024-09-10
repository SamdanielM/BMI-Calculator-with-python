# BMI-Calculator-with-python
This Python script calculates BMI based on weight (kg) and height (cm), then provides a personalized health risk assessment. It categorizes users as underweight, normal, overweight, obese, severely obese, or morbidly obese and gives relevant health advice based on their BMI.

name = input("Enter your Name" )
weight = int(input("Enter your Weight in Kg" )) 
height = int(input("Enter your Height in cm" )) 

BMI = (weight) / (height * height )
print(BMI)
if BMI>0:
    if(BMI<18.5):
        print(name + "you are underweight & your health risk is minimal gain some muscle")
    elif (BMI<=24.9):
        print(name + "You are normal weight & your health risk is minimal ur fitttt")
    elif (BMI<29.9):
        print(name + "you are over weight & your health risk is increased should be little catious")
    elif (BMI<34.9):
        print(name + "you are obese & your health risk in high lose some fat should me more catious")
    elif (BMI<39.9):
        print(name + "you severly obese & your health risk very high lose some fatttt")
    elif (BMI>40):
        print(name + "you morbidly obese & your health rish is extermly high lose more fatttttt")
    else:
        print("Enter valid Inputs")
