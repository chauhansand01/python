Q1. Python program to convert the temperature in degree cenƟgrade to Fahrenheit.
def celsius_to_fahrenheit(celsius):
 fahrenheit = (celsius * 9/5) + 32
 return fahrenheit
celsius = float(input("enter temperature in Celsius: "))
fahrenheit = celsius_to_fahrenheit(celsius)
print(f"{celsius}°C is equal to {fahrenheit}°F")
