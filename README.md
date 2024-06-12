[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15264464&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   - Python is a high-level, interpreted programming language known for its simplicity and readability.

   - FEATURES OF PYTHON THAT MAKE IT POPULAR
Readable and Maintainable Code: Python's syntax emphasizes readability, making it easier to understand and write clean code.
Wide Standard Library: Includes modules for various tasks such as web development, data analysis, machine learning, etc.
Dynamic Typing: No need to declare variable types explicitly.
Interpreted Language: Executes code line by line, which makes debugging easier.
Cross-Platform: Runs on various operating systems such as Windows, macOS, and Linux.
USE CASES WHERE PYTHON IS PARTICULARY EFFECTIVE
Web Development: Using frameworks like Django and Flask.
Data Analysis and Visualization: Using libraries like Pandas, NumPy, and Matplotlib.
Machine Learning and AI: Using TensorFlow, Keras, and Scikit-learn.

3. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

      STEPS IN INSTALLING PYTHON
     WINDOWS:
Download the installer from the official Python website.
Run the installer and ensure you check "Add Python to PATH".
Follow the installation prompts.
    MACOS:
Install Homebrew if you don't have it: /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Install Python: brew install python
    Linux:
Update package list: sudo apt update
Install Python: sudo apt install python3

VERIFY INSTALLATION
Open a terminal or command prompt and type: python --version

SETTING UP A VIRTUAL ENVIRONMENT
Install virtualenv; pip install virtualenv
Create a virtual environment: python -m venv myenv
Activate the virtual environment:
     Windows: myenv\Scripts\activate
     macOS/Linux: source myenv/bin/activate

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   - PYTHON PROGRAM THAT PRINTS HELLO WORLD
 print("Hello, World!")

EXPLANATION OF THE SYNTAX USED
print: A built-in function to output text to the console.
"Hello, World!": A string enclosed in double quotes. Single quotes can also be used.

5. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

      DATA TYPES IN PYTHON
int: Integer numbers.
float: Floating-point numbers.
str: Strings.
bool: Boolean values (True or False).
list: Ordered collection of items.
tuple: Ordered, immutable collection of items.
dict: Key-value pairs.
      SCRIPT ON HOW TO CREATE AND USE VARIALES OF DIFFERENT DATA TYPES
# Integer
age = 24
print("Age:", age)

# Float
height = 5.6
print("Height:", height)

# String
name = "Esther"
print("Name:", name)

# Boolean
is_graduate = True
print("Is student:", is_student)

# List
colors = ["red", "green", "blue"]
print("Colors:", colors)

# Tuple
coordinates = (10.0, 20.0)
print("Coordinates:", coordinates)

# Dictionary
person = {"name": "Esther", "age": 24}
print("Person:", person)


5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   - Conditional Statements:
Used to perform different actions based on different conditions.
Example:
x = 10
if x > 0:
    print("x is positive")
else:
    print("x is non-positive")

- Loops:
Used to execute a block of code repeatedly.

For Loop Example:
for i in range(4):
    print(i)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
 
-Functions:
Blocks of reusable code that perform a specific task. They help in organizing code, making it more modular, readable, and maintainable.
Example:
def add_numbers(x, y):
    return x + y

# Calling the function
result = add_numbers(3, 5)
print("Sum:", result)

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   - DEFINATION
Lists:Ordered collection of items. Indexed by position (starting from 0).
Dictionaries:Collection of key-value pairs. Indexed by keys (unique).
SCRIPT

# List
numbers = [1,2,3,4,5]
numbers.append(6)
print("Numbers:", numbers)
print("First number:", numbers[0])

# Dictionary
person = {"name": "Esther", "age": 24}
person["city"] = "Nairobi"
print("Person:", person)
print("Name:", person["name"])


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   - Exception Handling:
A mechanism to handle runtime errors, allowing the program to continue execution or fail gracefully.
Example:
try:
    num = int(input("Enter a number: "))
    result = 10 / num
    print("Result:", result)
except ZeroDivisionError:
    print("Error: Division by zero is not allowed.")
except ValueError:
    print("Error: Invalid input. Please enter a number.")
finally:
    print("Execution completed.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
     Modules:
Files containing Python code (functions, classes, variables).

    Packages:
Directories containing multiple modules and a special __init__.py file.

Example:
import math

print("Square root of 25 is:", math.sqrt(25))
print("Pi value is:", math.pi)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

      Reading from a File:
with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

      Writing to a File:
lines = ["Hello, World!", "Python is great!", "File I/O is easy."]
with open('output.txt', 'w') as file:
    for line in lines:
        file.write(line + '\n')



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


