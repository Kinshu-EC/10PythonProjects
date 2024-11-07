Expense Split Calculator
This project is an expense-splitting calculator that allows users to divide a total amount evenly or unevenly among a specified number of people, with an option to set custom split percentages for each person.

Features
Even Split: Splits the total amount equally among all participants.
Uneven Split: Allows each person to pay a different share based on specified percentages.
Error Handling: Ensures valid input for number of people, percentages, and amount to avoid miscalculations.
Currency Customization: The currency symbol can be customized (default is set to INR).

How to Use
Run the Script: Open and execute the script in a Python environment.
Input Required Information:
Total amount of the expense
Number of people sharing the expense
Specify whether you want an even or uneven split:
For an even split, the script will calculate each person's equal share.
For an uneven split, input the percentage each person will pay (ensuring the total adds up to 100%).
Review the Split Summary: The script will display each person’s share along with the total expense and the number of people involved.

Example
Even Split
Enter the total amount of the expense: 1000
Enter the number of people sharing the expense: 4
Do you want to split evenly or unevenly? (e/u): e

Each person should pay: INR 250.00
Total expenses: INR 1,000.00
Number of people: 4

Uneven Split
Enter the total amount of the expense: 1000
Enter the number of people sharing the expense: 3
Do you want to split evenly or unevenly? (e/u): u
Enter the split percentages for 3 people (must add up to 100):
Enter percentage for person 1: 40
Enter percentage for person 2: 35
Enter percentage for person 3: 25

Person 1 should pay: INR 400.00 (40%)
Person 2 should pay: INR 350.00 (35%)
Person 3 should pay: INR 250.00 (25%)
Total expenses: INR 1,000.00
Number of people: 3

Requirements
Python 3.x
