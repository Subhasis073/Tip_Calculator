# Tip_Calculator

**Description**
A simple Python program that helps you calculate how much each person should pay when splitting a bill, including a chosen tip percentage. The program asks for the bill amount, desired tip percentage (10, 12, or 15), and the number of people. It then calculates the tip, adds it to the bill, and splits the total evenly among the specified number of people.

**How It Works**

1. Greets the user.
2. Asks for the total bill amount.
3. Asks for the desired tip percentage.
4. Asks how many people will split the bill.
5. Calculates each person's share, including the tip, and displays the amount rounded to 2 decimal places.


**Operators used:**
/ (Division): Used to convert the tip percentage to a decimal and to divide the total bill among people.

* (Multiplication): Used to calculate the total tip amount based on the bill and tip percentage.

+ (Addition): Used to add the tip amount to the original bill.

= (Assignment): Used to assign values to variables.


**Functions:**
print(): Displays messages and results to the user.

input(): Takes input from the user as a string.

float(): Converts the bill input string to a floating-point number.

int(): Converts the tip percentage and number of people inputs to integers.

round(): Rounds the final amount to 2 decimal places for currency formatting.

f-string (f""): Formats the output message with the calculated final amount.

