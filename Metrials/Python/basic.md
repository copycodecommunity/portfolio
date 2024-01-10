
## 1. Basics:

### Structure of a Python Program:
```python
# This is a comment
print("Hello, World!")
```

### Variables:
```python
num = 10            # Integer
floatNum = 3.14     # Floating-point
stringVar = "Hello" # String
```

### Input/Output:
```python
user_input = input("Enter something: ")  # Input
print("You entered:", user_input)        # Output
```

## 2. Data Types:

### Primitive Data Types:
```python
int, float, str, bool
```

### Collections:
```python
listVar = [1, 2, 3]           # List
tupleVar = (1, 2, 3)          # Tuple
setVar = {1, 2, 3}            # Set
dictionaryVar = {'key': 'value'}  # Dictionary
```

## 3. Operators:

### Arithmetic Operators:
```python
+, -, *, /, %, **
```

### Relational Operators:
```python
==, !=, <, >, <=, >=
```

### Logical Operators:
```python
and, or, not
```

## 4. Control Flow:

### if-else Statement:
```python
if condition:
    # Code block if true
else:
    # Code block if false
```

### Loop:

#### while Loop:
```python
while condition:
    # Code block
```

#### for Loop:
```python
for item in iterable:
    # Code block
```

## 5. Functions:

### Function Declaration:
```python
def my_function(parameters):
    # Code block
    return value
```

### Function Call:
```python
result = my_function(arguments)
```

### Lambda Functions:
```python
multiply = lambda x, y: x * y
```

## 6. Classes and Objects:

### Class Declaration:
```python
class MyClass:
    def __init__(self, attribute):
        self.attribute = attribute

    def my_method(self):
        # Code block
```

### Object Creation:
```python
obj = MyClass("example")
obj.my_method()
```

## 7. Exception Handling:

### try-except Block:
```python
try:
    # Code that might raise an exception
except ExceptionType as e:
    # Handle the exception
```

## 8. File Handling:

### Reading from a File:
```python
with open('filename.txt', 'r') as file:
    content = file.read()
```

### Writing to a File:
```python
with open('filename.txt', 'w') as file:
    file.write("Hello, File!")
```

## 9. Libraries and Modules:

### Importing a Module:
```python
import module_name
```

### Common Libraries:
```python
import math, random, datetime
```

## 10. Virtual Environments:

### Creating a Virtual Environment:
```bash
python -m venv venv_name
```

### Activating a Virtual Environment:
- **Windows:**
  ```bash
  .\venv_name\Scripts\activate
  ```
- **Linux/Mac:**
  ```bash
  source venv_name/bin/activate
  ```

### Installing Packages:
```bash
pip install package_name
```

### Deactivating a Virtual Environment:
```bash
deactivate
```

This cheatsheet covers a broad range of Python programming concepts. Feel free to refer to it as a quick reference guide and expand it based on your specific needs.