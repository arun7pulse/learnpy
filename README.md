# 1. Basic Syntax
Python syntax is simple and straightforward. Here's an overview:

Key Features:
Case Sensitivity:
Python distinguishes between uppercase and lowercase (e.g., name and Name are different variables).

Indentation:
Indentation (spaces or tabs) is used to define code blocks, such as in loops or functions. Improper indentation will result in an error.
Example:

python
```
for i in range(3):  # Correct indentation
    print(i)
```
## Incorrect indentation will cause an error

Comments:
Use # for single-line comments and triple quotes (''' or """) for multi-line comments.

python

```
## This is a single-line comment
```
```
"""
This is a multi-line comment
explaining the purpose of the code.
"""
```
Semicolons and Braces:
Python does not require semicolons to terminate lines or braces to define blocks.

# 2. Variables
A variable stores data. You don't need to declare its type explicitly in Python because it’s dynamically typed.

Rules for Naming Variables:
Must start with a letter or underscore (_).
Can contain letters, numbers, and underscores but cannot start with a number.
Should not use Python keywords (e.g., if, for, class).
Examples:
python


# Valid variable names

```
age = 25
_name = "Alice"
number_1 = 100
```

# Invalid variable names
```
1name = "Bob"  # Cannot start with a number
class = 10     # 'class' is a keyword
```
# 3. Data Types
Python has several built-in data types. Here’s a breakdown of the most common ones:

A. Numeric Types
Integer (int): Whole numbers (e.g., 10, -5).
Example:

python
```
age = 30
print(type(age))  # Output: <class 'int'>
```
Floating-point (float): Numbers with decimals (e.g., 3.14, -2.5).
Example:

python
```
pi = 3.14159
print(type(pi))  # Output: <class 'float'>
```
B. String (str)
Text data enclosed in single or double quotes (e.g., "Hello", 'Python').
Example:

python
```
message = "Hello, Python!"
print(type(message))  # Output: <class 'str'>
String Operations:
Concatenation:
```

python
```
greeting = "Hello" + " World"
print(greeting)  # Output: Hello World
Repetition:
```
python
```
print("Python! " * 3)  # Output: Python! Python! Python!
Access characters:
```
python
```
name = "Alice"
print(name[0])  # Output: A
print(name[-1]) # Output: e
```
C. Boolean (bool)
Logical values: True or False.
Example:

python
```
is_valid = True
print(type(is_valid))  # Output: <class 'bool'>
```
# 4. Variable Assignment
Variables in Python can be reassigned to different data types because of dynamic typing.

Example:
python
```
x = 10           # Integer
print(x)

x = "Hello"      # String
print(x)
```

# 5. Type Conversion
You can convert one data type into another using built-in functions like int(), float(), str(), etc.

Examples:
python

```
# Convert string to integer

age = int("25")
print(age)  # Output: 25
```

```
# Convert integer to string
age_str = str(25)
print(age_str)  # Output: "25"
```

```
# Convert string to float

pi = float("3.14")
print(pi)  # Output: 3.14
```


# 6. Data Type Checking
You can check the type of a variable using the type() function.

Example:
python

```
x = 10
print(type(x))  # Output: <class 'int'>

y = "Hello"
print(type(y))  # Output: <class 'str'>
```




# Data Type:
integer  
floating
boolean 
String site="google.com"
String site1="facebook.com"

strlist = [
    "google.com",
    "faceook.com"
]
Data Struture 
list [1,2,3,4,5,5]
list[
    "google.com",
    "faceook.com"
]
Set (2,1,3,4,5)
Dict {"name":arun, number:9378468374}
Tuple (1,2,3,4)

numpy 
Pandas
parquet
arrowtable



# Opeartors:

Numerical Operators
- "+"


Comparision Operators
Logical Operators
Assignment Operators



# Formating String 

placeholders:
%s - String
%d - Integer
%f - Float (you can specify precision, e.g., %.2f for 2 decimal places)
%x - Hexadecimal

