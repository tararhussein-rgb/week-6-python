
# PLP Python Week 6 Assignment

## Assignment Title
Safe Functions Using Try and Except

## Project Files

### safe_tools.py
Contains three safe functions:
- safe_divide() handles division by zero using ZeroDivisionError.
- safe_number() converts text into an integer and handles ValueError.
- get_field() retrieves dictionary values and handles KeyError.

### README.md
Contains the project description and explanation of error handling.

## Question: Why can the if check not catch abc on its own?

An if statement cannot directly catch a ValueError when converting text into an integer. The int() function raises an error when the input is not a valid number. Therefore, try and except are used to catch the ValueError and prevent the program from crashing.
