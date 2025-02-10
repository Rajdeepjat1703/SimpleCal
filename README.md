Calculator Program

Description

This Java program evaluates mathematical expressions entered by the user. It supports basic arithmetic operations including addition, subtraction, multiplication, and division, along with handling parentheses for precedence.

Features

Supports +, -, *, and / operations

Handles operator precedence and parentheses

Supports floating-point numbers

Provides error handling for invalid expressions and division by zero

Runs in a loop until the user types exit

How to Use

Run the program.

Enter a mathematical expression (e.g., 3 + 5 * (2 - 8)).

The result will be displayed.

Type exit to terminate the program.

Code Structure

Main class: Contains the logic for parsing and evaluating expressions.

evaluate(String expression): Parses the input and computes the result using two stacks.

applyOp(char op, double b, double a): Performs arithmetic operations.

precedence(char op): Determines operator precedence.

isOperator(char c): Checks if a character is an operator.
![image](https://github.com/user-attachments/assets/586b6716-4540-47c7-a718-f8ef27eb826a)


