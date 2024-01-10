
## 1. **Class and Object:**

### Class Declaration:
```python
class Car:
    def __init__(self, make, model):
        self.make = make
        self.model = model

    def display_info(self):
        print(f"{self.make} {self.model}")
```

### Object Creation:
```python
car1 = Car("Toyota", "Camry")
car2 = Car("Honda", "Civic")

car1.display_info()  # Output: Toyota Camry
car2.display_info()  # Output: Honda Civic
```

## 2. **Attributes and Methods:**

### Attributes (Properties):
Attributes represent the characteristics or properties of an object.

```python
class Dog:
    def __init__(self, name, age):
        self.name = name
        self.age = age
```

### Methods (Functions):
Methods represent the behavior or actions an object can perform.

```python
class Dog:
    def bark(self):
        print("Woof!")

my_dog = Dog("Buddy", 3)
my_dog.bark()  # Output: Woof!
```

## 3. **Inheritance:**

Inheritance allows a new class (subclass/derived class) to inherit attributes and methods from an existing class (superclass/base class).

```python
class Animal:
    def speak(self):
        pass

class Dog(Animal):
    def speak(self):
        print("Woof!")

class Cat(Animal):
    def speak(self):
        print("Meow!")

dog = Dog()
cat = Cat()

dog.speak()  # Output: Woof!
cat.speak()  # Output: Meow!
```

## 4. **Encapsulation:**

Encapsulation restricts access to some of an object's components and prevents the accidental modification of data.

```python
class BankAccount:
    def __init__(self, balance):
        self._balance = balance  # Protected attribute

    def get_balance(self):
        return self._balance

    def deposit(self, amount):
        self._balance += amount

    def withdraw(self, amount):
        if amount <= self._balance:
            self._balance -= amount
        else:
            print("Insufficient funds.")
```

## 5. **Polymorphism:**

Polymorphism allows objects of different classes to be treated as objects of a common base class. It enables flexibility in handling different data types.

### Method Overriding:
```python
class Bird:
    def make_sound(self):
        pass

class Sparrow(Bird):
    def make_sound(self):
        print("Chirp!")

class Parrot(Bird):
    def make_sound(self):
        print("Squawk!")

sparrow = Sparrow()
parrot = Parrot()

sparrow.make_sound()  # Output: Chirp!
parrot.make_sound()   # Output: Squawk!
```

## 6. **Abstraction:**

Abstraction simplifies complex systems by providing a simplified view. It involves hiding the unnecessary details while exposing the essential features.

```python
from abc import ABC, abstractmethod

class Shape(ABC):
    @abstractmethod
    def area(self):
        pass

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius

circle = Circle(5)
print(circle.area())  # Output: 78.5
```

These core OOP concepts provide a foundation for building scalable and modular software systems. By utilizing these principles, developers can create reusable, maintainable, and organized code. Understanding OOP is crucial for effective software design and development.