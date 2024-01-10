
## 1. Basics:

### Structure of a C Program:
```c
#include <stdio.h>

int main() {
    // Your code here
    return 0;
}
```

### Variables:
```c
int num;            // Integer
float floatNum;     // Floating-point
char character;     // Character
```

### Input/Output:
```c
printf("Hello, World!\n");   // Output
scanf("%d", &num);           // Input
```

## 2. Data Types:

### Primitive Data Types:
```c
int, float, double, char
```

### Modifiers:
```c
short, long, signed, unsigned
```

## 3. Operators:

### Arithmetic Operators:
```c
+, -, *, /, %
```

### Relational Operators:
```c
==, !=, <, >, <=, >=
```

### Logical Operators:
```c
&&, ||, !
```

## 4. Control Flow:

### if-else Statement:
```c
if (condition) {
    // Code block if true
} else {
    // Code block if false
}
```

### Switch Statement:
```c
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
```c
while (condition) {
    // Code block
}
```

#### for Loop:
```c
for (initialization; condition; update) {
    // Code block
}
```

## 5. Functions:

### Function Declaration:
```c
returnType functionName(parameters) {
    // Code block
    return value;
}
```

### Function Call:
```c
result = functionName(arguments);
```

## 6. Arrays:

### Declaration:
```c
int numbers[5];    // Array of integers
```

### Initialization:
```c
int numbers[] = {1, 2, 3, 4, 5};
```

### Accessing Elements:
```c
value = numbers[index];
```

## 7. Pointers:

### Declaration:
```c
int *ptr;
```

### Initialization:
```c
int num = 10;
int *ptr = &num;
```

### Accessing Value via Pointer:
```c
value = *ptr;
```

## 8. Memory Management:

### Dynamic Memory Allocation:
```c
int *dynamicArray = (int*)malloc(5 * sizeof(int));
```

### Freeing Allocated Memory:
```c
free(dynamicArray);
```

---

This cheatsheet covers some of the basics in C programming. Feel free to expand it with more advanced topics as needed.