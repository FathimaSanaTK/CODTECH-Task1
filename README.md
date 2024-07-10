Name: FATHIMA SANA THACHAR KANDI
Company: CODTECH IT SOLUTIONS
ID: 
Domain: Python Programming
Duration: June to July 2024
Mentor: SRAVANI GOUNI

Overview of MyCalculator Project
Purpose:
The purpose of this program is to perform basic arithmetic operations (addition, subtraction, multiplication, and division) based on user input and provide an interactive experience where users can continue performing operations until they choose to exit.

Features:

Arithmetic Operations: The program can perform addition, subtraction, multiplication, and division.
User Choice: Users can choose which arithmetic operation they want to perform.
Continuous Interaction: The program allows users to perform multiple calculations in a loop until they choose to exit.
Input Validation: Basic validation to handle invalid operation choices.

Components:

User Interface:
Prints a welcome message.
Provides a menu for users to choose the arithmetic operation.
Input Handling:
Prompts the user to enter their choice of operation.
Prompts the user to input two numbers for the calculation.
Arithmetic Operations:
Uses a match statement (Python 3.10+ syntax) to perform the chosen arithmetic operation.
Handles invalid operation choices with a default case.
Result Display:
Prints the result of the arithmetic operation.
Loop Control:
Asks the user if they want to continue performing operations.
Exits the loop if the user chooses 'n'.

Workflow:

Initial Message:
Displays a welcome message.
Operation Choice:
Displays a menu of operations.
Prompts the user to enter their choice.
Input Numbers:
Prompts the user to enter two numbers for the operation.
Perform Operation:
Uses the match statement to perform the chosen operation.
Handles any invalid input by printing an error message.
Display Result:
Prints the result of the operation.
Continue or Exit:
Asks the user if they want to continue.
Continues the loop if the user chooses 'y'.
Exits the loop if the user chooses 'n'.

Example:

Welcome to MyCalculator!!
1.Addition
2.Subtraction
3.Multiplication
4.Division
Enter your choice:
1
Enter the numbers:
10
20
Answer =  30.0
Do you want to continue?(y/n): 
y
1.Addition
2.Subtraction
3.Multiplication
4.Division
Enter your choice:
4
Enter the numbers:
20
5
Answer =  4.0
Do you want to continue?(y/n): 
n

Summary:

This program provides a simple, interactive calculator that can perform basic arithmetic operations. It continuously prompts the user for input and performs the requested calculations until the user decides to exit. The program is designed to be user-friendly and offers basic validation for operation choices, ensuring a smooth user experience. It can be extended with additional features such as more complex operations, error handling for invalid number inputs, or a graphical user interface (GUI) for enhanced usability.
