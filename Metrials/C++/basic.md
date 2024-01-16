
## 1. Basics:

### Structure of a C++ Program:
```cpp
#include <iostream>

int main() {
    // Your code here
    return 0;
}
```

### Variables:
```cpp
int num;                // Integer
float floatNum;         // Floating-point
char character;         // Character
```

### Input/Output:
```cpp
std::cout << "Hello, World!" << std::endl;   // Output
std::cin >> num;                              // Input
```

## 2. Data Types:

### Primitive Data Types:
```cpp
int, float, double, char, bool
```

### Modifiers:
```cpp
short, long, signed, unsigned
```

### Strings:
```cpp
std::string myString = "Hello";
```

## 3. Operators:

### Arithmetic Operators:
```cpp
+, -, *, /, %
```

### Relational Operators:
```cpp
==, !=, <, >, <=, >=
```

### Logical Operators:
```cpp
&&, ||, !
```

## 4. Control Flow:

### if-else Statement:
```cpp
if (condition) {
    // Code block if true
} else {
    // Code block if false
}
```

### Switch Statement:
```cpp
switch (expression) {
    case constant1:
        // Code block
        break;
    case constant2:
        // Code block
        break;
    // ...
    default:
        // Code block if no match
}
```

### Loops:

#### while Loop:
```cpp
while (condition) {
    // Code block
}
```

#### for Loop:
```cpp
for (initialization; condition; update) {
    // Code block
}
```

## 5. Functions:

### Function Declaration:
```cpp
returnType functionName(parameters) {
    // Code block
    return value;
}
```

### Function Call:
```cpp
result = functionName(arguments);
```

## 6. Classes and Objects:

### Class Declaration:
```cpp
class MyClass {
public:
    int myVariable;
    void myMethod();
};
```

### Object Creation:
```cpp
MyClass obj;
obj.myVariable = 10;
obj.myMethod();
```

## 7. Inheritance:

### Base Class:
```cpp
class BaseClass {
public:
    // Base class members
};
```

### Derived Class:
```cpp
class DerivedClass : public BaseClass {
public:
    // Derived class members
};
```

## 8. Pointers:

### Declaration:
```cpp
int *ptr;
```

### Initialization:
```cpp
int num = 10;
int *ptr = &num;
```

### Accessing Value via Pointer:
```cpp
value = *ptr;
```

## 9. Standard Template Library (STL):

### Vectors:
```cpp
#include <vector>
std::vector<int> myVector;
```

### Maps:
```cpp
#include <map>
std::map<std::string, int> myMap;
```

---

This cheatsheet covers some of the basics in C++ programming. Feel free to expand it with more advanced topics and features of C++ as needed.
