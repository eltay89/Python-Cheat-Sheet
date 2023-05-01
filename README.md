# Python Cheat Sheet

```python
# Variables and Data Types

# Creating variables
name = "John"
age = 25
height = 1.75
is_student = True

# Data types
string = "Hello, World!"
integer = 42
float = 3.14
boolean = True


# Control Structures

# If statement
if x > 0:
    print("x is positive")
elif x == 0:
    print("x is zero")
else:
    print("x is negative")

# For loop
for i in range(10):
    print(i)

# While loop
while x < 10:
    print(x)
    x += 1


# Functions

# Defining a function
def greet(name):
    print("Hello, " + name + "!")

# Calling a function
greet("John")


# Lists and Dictionaries

# Creating a list
fruits = ["apple", "banana", "cherry"]

# Accessing list elements
print(fruits[0])
print(fruits[-1])

# Adding elements to a list
fruits.append("orange")
fruits.insert(1, "pear")

# Creating a dictionary
person = {"name": "John", "age": 25, "is_student": True}

# Accessing dictionary elements
print(person["name"])
print(person.get("age"))

# Adding elements to a dictionary
person["height"] = 1.75
person.update({"weight": 70})


# File Handling

# Reading from a file
with open("file.txt", "r") as f:
    contents = f.read()
