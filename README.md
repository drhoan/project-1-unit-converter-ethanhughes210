mile = float(input("Enter the mile you wish to convert. Enter 0 to skip (m): "))  
if mile == 0:
   print("Next Question")
kilometer = []  # Using a list to store the converted value  
kilometer.append(mile * 1.60934)  # Correct conversion  

for i in kilometer:  
    print(i)  # Printing the converted value  


print('___________________________________________________________________________-')

inch = float(input("Enter the inch you wish to convert (i): "))  
if inch == 0:
   print("Next Question")
centimeter = []  # Using a list to store the converted value  
centimeter.append(inch * 2.54)  # Correct conversion  

for i in centimeter:
    print(i)

print('___________________________________________________________________________')

pound = float(input("Enter the pound you wish to convert (pound): "))  
if pound == 0:
   print("Next Question")
dollar = []  # Using a list to store the converted value  
dollar.append(pound * 1.294)  # Correct conversion  

for i in dollar:
    print(i)

print('___________________________________________________________________________')

ton = float(input("Enter the ton you wish to convert (pound): "))  
if ton == 0:
   print("Next Question")
pounds = []  # Using a list to store the converted value  
pounds.append(ton * 2000)  # Correct conversion  

for i in pounds:
    print(i)

print('___________________________________________________________________________')

kelvin = float(input("Enter the kelvin you wish to convert (celcius): "))  
if kelvin == 0:
   print("Skip Unavaliable")
celcius = []  # Using a list to store the converted value  
celcius.append(kelvin + 273)  # Correct conversion  

for i in celcius:
    print(i)

Enter task 1: temp, 2: weight, 3: distance (0 for quit): 1 <br>
OK, let's convert temperature in Fahrenheit to Celcius <br>
Enter temperature in F: 2 <br>
Result: 2.0 F is -16.666666666666668 C

Enter task 1: temp, 2: weight, 3: distance (0 for quit): 0 <br>
See you next time
