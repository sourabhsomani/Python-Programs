# Python-Programs
Python Basics Programs 

## Hello World
```Python
print("Hello world!")
```
## Python Keywords
Keywords are the reserved words in Python.
You can print all keywords 
```Python
help('keywords')
```
**Keywords List**
| | | | |
|-|-|-|-|
|False|def|if|raise|
|None|del|import|return|
|True|elif|in|try|
|and|else|is|while|
|as|except|lambda|with|
|assert|finally|nonlocal|yield|
|break|for|not|
|class|from|or|
|continue|global|pass|

Except `True`, `False` and `None` all keywords are in lowercase.

## Python Identifiers
Identifier is the user defined name for any element of the program like class, functions, variables etc.
**Rules**
1. Can be a combination of letters(a-z or A-Z) or digit(0-9) or underscore(_).
2. Cannot be start with number.
3. Cannot be keywords

> Python is a case-sensitive language

## Statement 
### Single Line Statements
```python
number=1 + 2 + 3
name="Sourabh Somani"
```
### Multiline Statements
```python
number=1 + 2 + 3 \
       4 + 5 + 6 \
       7 + 8 + 9 \
       10
name = "Sourabh \
       Somani"
matrix = [[1,2,3],
         [4,5,6],
         [7,8,9]]
```
## Python Comments
### Single-line Comment
```python
#this is single line comment
```
### Multi-line Comment
```python
"""
Multi 
line 
comment 
"""
'''
Multi 
line 
comment 
'''
```

## Variable in Python
variable is a named location used to store data in the memory. 
### Declaring and Assigning Variable
```Python
x=10
```

## Constants
Variable whose value cannot be changed called Constants.
**How to create constant?**
1. Create a file Constants.py file and You can write following code
```Python
PI=3.14
C=299,792,458 # Ligth Speed in vacuum
g= 9.80665 # standard gravity
```
2. Now you can import that file in your main file where you want to use constant.
```Python
import constant
print(constant.PI)
print(constant.C)
print(constant.g)
```

## Literals
Literal is a raw data given in a variable or constant.
### Numeric Literals
```Python
z = 0b1011 #Binary Literals
y = 104 #Decimal Literal 
x = 0o712 #Octal Literal
w = 0x13F #Hexadecimal Literal

#Float Literal
f1 = 126.521 
f2 = 6.25e2

#Complex Literal 
x = 3+2j
```
### String literals
```Python
str = "Hello Pyhton Babu"
char = "S"
multiline_str = """This is 
                   a multiline 
                string"""
unicode = u"\u00dcnic\u00f6de"
raw_str = r"This is raw \n string"
```

### Boolean literals
```Python
a = True + 3
b = False + 3
```

## Python Data Types
[Python Data Type You can Learn From Here](https://www.c-sharpcorner.com/UploadFile/75a48f/python-data-types/)

## Python Print Function
[About Print Function](https://www.pythonbabu.com/learn/Python-Jumpstart/Python-print-function)

## Python Input
To take input from the user we use Python Input Function
**Syntax**
```Python
input([prompt=None])
```
**Example**
```Python
Name = input("What is your Name?")
print("Hello",Name)
```

## Python Operators
[Python Operatorrs](https://www.c-sharpcorner.com/UploadFile/75a48f/python-operators/)

## Decision Making Statements in Python
[Decision Making Statements In Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-if-else-nested-if-elif/)

## While Loop in Python
[While Loop in Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-while-loop566/)

## For Loop in Python
[For loop in Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-for-loop553/)

## Break Continue and Pass in Python
[Break Continue and Pass in Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-break-and-continue847/)

## Python DateTime
[Working With Date And Time In Python](https://www.c-sharpcorner.com/UploadFile/75a48f/working-with-date-and-time-python/)

## Math Functions in Python
[Math Function in Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-math-function/)

## Function and Name Space in Python
[Functions in Python](https://www.c-sharpcorner.com/UploadFile/75a48f/python-function/)
