# weight-Temperature-converter

# weight converter
weight = float(input("Enter your weight: "))
unit = input("weight in Kilograms or Pounds? (K or L): ").upper()

if unit == "K":
    weight = weight * 2.205
    unit = "Lbs"
    print(f"Your weight is: {weight} {unit}")

elif unit == "L":
    weight = weight / 2.205
    unit = "Kgs"
    print(f"Your weight is: {weight} {unit}")

else:
    print(f"{unit} was not valid")



# Temperature Converter

unit = input("Is this temperature in celcious or Faranheit (C/F): ").upper()
temp = float(input("Enter the temperature: "))

if unit == "C":
    temp = (9 * temp) / 5 + 32
    print(f"The temperature in Faranheit is {temp}")

elif unit =='F':
    temp = (temp - 32) * 5 / 9
    print(f"The temperature in celcious is {temp}")

else:
    print(f"{unit} is an invalid unit of measurnment")
