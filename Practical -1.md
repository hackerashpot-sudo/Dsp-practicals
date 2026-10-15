Aim: Write a program to understand Python building blocks, data types, and basic
input-output operations by creating a student data system.
Theory:
Python is a simple, interpreted, and high-level programming language widely used for
developing applications. A Python program is built using basic elements called building
blocks, which include variables, data types, operators, input/output functions, and
expressions.
In this experiment, a Student Data System is created to take student information from the
user, process it, and display the results.
🧱 1. Python Building Blocks
Python programs are made up of:
● Variables: Used to store data values
Example: name = "Rahul"
● Keywords: Reserved words like if, else, print
● Expressions: Combination of variables and operators
Example: marks >= 40
● Statements: Instructions executed by Python
Example: print("Hello")
● Comments: Used for explanation and ignored by interpreter
Example: # This is a comment

 🧮 2. Data Types in Python
Python supports multiple data types: 🔹 Basic Data Types
● int → Integer values (e.g., 10, 25)
● float → Decimal values (e.g., 78.5)
● str → Text or string values (e.g., "John")
● bool → Logical values (True/False) 🔹 Example in Program:
● Name → str
● Roll number → int
● Marks → float
● Result (Pass/Fail) → bool
⌨ 3. Input and Output Operations
🔹 Input Function
● input() is used to take data from the user.
● It always returns data in string format unless converted.
Example:
name = input("Enter name: ")
🔹 Output Function
● print() is used to display output on the screen.
Example:
print("Student Name:", name)
🔄 4. Processing Logic Used
The program performs simple processing such as:
● Accepting student details
● Converting input into required data types
● Calculating pass/fail condition using logical expression:
 marks >= 40
 Displaying formatted results
Program:
# Student Data System
# Demonstrates Python building blocks, data types, and I/O
print("=== Student Data System ===")
# Input section (user provides data)
name = input("Enter student name: ") # str
roll_no = int(input("Enter roll number: ")) # int
age = int(input("Enter age: ")) # int
marks = float(input("Enter marks: ")) # float
is_pass = marks >= 40 # bool (logical expression)
# Processing section
percentage = (marks / 100) * 100
# Output section
print("\n=== Student Details ===")
print("Name:", name)
print("Roll Number:", roll_no)
print("Age:", age)
print("Marks:", marks)
print("Percentage:", percentage)
print("Result:", "Pass" if is_pass else "Fail")
# Display data types (to understand building blocks)
print("\n=== Data Types Used ===")
print("Type of name:", type(name))
print("Type of roll_no:", type(roll_no))
print("Type of age:", type(age))
print("Type of marks:", type(marks))
print("Type of is_pass:", type(is_pass))
Conclusion: Hence we have successfully understood Python building blocks, data types, andbasic input-output operations by creating a student data system.
