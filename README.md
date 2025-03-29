[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/aRpelc5q)
# unit-converter-project
Project 1: Creating a Unit Converter

In this project, you will create a Python Program that:
1. Allows user to choose what kind of unit conversion he/she wants to do.
Examples of unit conversion are: temperature in Farenheit to Celcius, weight in Pound to Kg, distance in Feet to Meter, etc.
Your program should have at least 5 different options for user to choose
3. After user chose one of the unit conversions (e.g., temp), the program asks user for quantity in one unit (temp in F) and the program prints out quantity in another unit (temp in C).
The program then repeat step 1 until user enter 0.
Then program stop and print a nice goodbye message to the user.
Sample output:

Enter task 1: temp, 2: weight, 3: distance (0 for quit): 3 <br>
OK, let's convert distance in feet to meter <br>
Enter distance in feet: 3 <br>
Result: 3.0 feet is 0.9144000000000001 meter

Enter task 1: temp, 2: weight, 3: distance (0 for quit): 2 <br>
OK, let's convert weight in pound to kg <br>
Enter weight in pound: 1 <br>
Result: 1.0 pound is 0.453592 kg


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
