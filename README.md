Python Cheat Sheet

This cheat sheet provides a quick reference for common Python syntax and concepts.
Contents

    Variables and Data Types
    Conditional Statements
    Loops
    Functions
    Lists
    Dictionaries
    Classes and Objects
    Modules

Variables and Data Types

Python is dynamically typed, meaning that you don't need to specify the type of a variable when you declare it. Here are some common data types:

python

# integers
x = 5

# floating-point numbers
y = 3.14

# strings
message = "Hello, world!"

# boolean values
is_true = True
is_false = False

Conditional Statements

Conditional statements are used to execute code only when certain conditions are met. Here's an example of an if statement:

python

x = 5

if x > 0:
    print("x is positive")
elif x == 0:
    print("x is zero")
else:
    print("x is negative")

Loops

Loops are used to repeat code until a certain condition is met. Here's an example of a for loop:

python

fruits = ["apple", "banana", "cherry"]

for fruit in fruits:
    print(fruit)

And here's an example of a while loop:

python

i = 1

while i < 6:
    print(i)
    i += 1

Functions

Functions are blocks of code that can be reused throughout a program. Here's an example of a function that adds two numbers:

python

def add_numbers(x, y):
    return x + y

Lists

Lists are used to store collections of items. Here's an example of a list:

python

fruits = ["apple", "banana", "cherry"]

You can access individual elements of a list using their index:

python

print(fruits[0])  # "apple"

Dictionaries

Dictionaries are used to store key-value pairs. Here's an example of a dictionary:

python

person = {"name": "John", "age": 30, "city": "New York"}

You can access individual values of a dictionary using their keys:

python

print(person["name"])  # "John"

Classes and Objects

Classes are used to define custom data types, and objects are instances of those types. Here's an example of a class:

python

class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age

    def greet(self):
        print(f"Hello, my name is {self.name} and I am {self.age} years old.")

You can create objects of a class using the class constructor:

python

person = Person("John", 30)
person.greet()  # "Hello, my name is John and I am 30 years old."

Modules

Modules are used to organize code into separate files. Here's an example of how to import a module:

python

import math

x = math.sqrt(25)
print(x)  # 5.0
