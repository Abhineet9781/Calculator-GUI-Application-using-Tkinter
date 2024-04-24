# Calculator-GUI-Application-using-Tkinter

This is a simple calculator application built using Python's tkinter library. It allows basic arithmetic operations (addition, subtraction, multiplication, and division) on integers.

Usage
Input Display
The calculator display is located at the top and shows the current input or result.
Buttons
The calculator provides numeric buttons (0-9) and operation buttons (+, -, *, /) for performing calculations.
Use the numeric buttons to enter numbers.
Use the operation buttons to perform arithmetic operations.
Clear Button (C)
Press the "C" button to clear the input and reset the calculator.
Equal Button (=)
Press the "=" button to calculate the result based on the current input expression.
Instructions
Installation
Clone the repository or download the Calculator.py file.
Dependencies
Ensure you have Python installed on your system.
No additional libraries are required beyond the standard Python library.
Execution
Run Calculator.py using Python.
The calculator window will appear, allowing you to perform calculations.
Example
Basic Calculation
Enter numbers using the numeric buttons.
Use the operation buttons to perform calculations.
Press "=" to see the result displayed.
Clear Input
Press "C" to clear the input field and start a new calculation.
Code Details
The calculator logic is implemented using Python and tkinter for the graphical user interface (GUI). The main features of the code include:

Event handling for button clicks (btnClick, btnClear, btnEquals).
Updating the display based on user input and calculated results.
Utilizing eval() to evaluate arithmetic expressions.

Notes
This calculator supports basic arithmetic operations and integer calculations.
The use of eval() can be dangerous with untrusted input. Ensure the input is sanitized to avoid security risks.
