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

## Lambda Function or Anonymous Function in Python
**Syntax**
```Python
lambda arguments: expression
```

**Example**
```Python
double = lambda x: x * 2

lst = [1,2,3,4,5,6,7,8,9,10]
EvenData=list(filter(lambda x: (x%2 == 0) , lst))

my_list = [1, 5, 4, 6, 8, 11, 3, 12]
new_list = list(map(lambda x: x * 2 , my_list))
```

## Module in Python 
- Creating Module 
Saving a file with function or a class and we can use that file in different-2 places
- Importing 
import keyword we use to import anything from the file. We can use `as` and `from` keyword while importing 
```python
from math import pi
import math as m
```

### Python Module Search Path
While importing a module, Python looks at several places. Interpreter first looks for a built-in module then (if not found) into a list of directories defined in sys.path. The search is in this order.

The current directory.
`PYTHONPATH` (an environment variable with a list of directory).
The installation-dependent default directory.

```Python
import sys
sys.path
```

### Reloading Module
To reload you can't use import many times you can use reload method of *imp* module 

```Python
import imp
import moduleName
imp.reload(moduleName)
```

### dir function
We can use the dir() function to find out names that are defined inside a module.
```Python
import math
dir(math)
```

## Working with file 
1. Open a file
2. Read or write (perform operation)
3. Close the file

### Open
```Python
f = open("FileName");
```
### Python File Mode
|Mode|Description|
|-|-|
| 'r' | Open a file for reading. (default)|
| 'w' | Open a file for writing. Creates a new file if it does not exist or truncates the file if it exists.|
| 'x' | Open a file for exclusive creation. If the file already exists, the operation fails.|
| 'a' | Open for appending at the end of the file without truncating it. Creates a new file if it does not exist.|
| 't' | Open in text mode. (default)|
| 'b' | Open in binary mode.|
| '+' | Open a file for updating (reading and writing)|

```Python
f = open("FileName",'w')
f = open("FileName",'r+b')
```
```Python
f.close()
```
