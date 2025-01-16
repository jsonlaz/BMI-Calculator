# BMI Calculator with Categorization

name = input("Enter your first name: ")

height = float(input("Enter your height in centimeters: "))

weight = float(input("Enter your weight in kilogram: "))

# Calculate BMI
BMI_cal = (weight) / (height/100)**2

BMI = round(BMI_cal, 1)

# Display the BMI
print(f"{name}, your BMI is {BMI}.")

# Categorize BMI
if BMI > 0:
    if (BMI < 16):
        print(name + ", you are severely thin.")
    elif (BMI < 17):
        print(name + ", you are moderately thin.")
    elif (BMI < 18.5):
        print(name + ", you are mildly thin.")
    elif (BMI < 25):
        print(name + ", you are normal.")
    elif (BMI < 30):
        print(name + ", you are overweight.")
    elif (BMI < 35):
        print(name + ", you are obese class I.")
    elif (BMI <= 40):
        print(name + ", you are obese class II.")
    else:
        print(name + ", you are obese class III.")
else:
    print("Please enter valid input values for height and weight.")
