# CS361_Calculator
# Microservice for CS 361

To use:

Calculations are transmitted through text.txt file included in this repo. 
To send a calculation, edit text.txt to read "operation, operand1, operand2(optional)"
Ex: "add, 1, 2", "multiply, 45, 2", "sin, 45"

Arithmetic calculations accepted: add, subtract, multiply, divide
Trig functions accepted: sin, cos, tan, asin, acos, atan

After reading text.txt, the microservice will replace all text with the result. If the request was unable to complete (divide by zero error, operands out of range, etc), the response will hold an error code.
