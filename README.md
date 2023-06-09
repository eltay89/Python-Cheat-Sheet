# Python Cheat Sheet

## Table of Contents
1. Variables and Data Types
2. Control Structures
3. Functions
4. Lists and Dictionaries
5. File Handling

## 1. Variables and Data Types

### Creating variables
```python
name = "John"     # creates a variable 'name' with the value "John"
age = 25          # creates a variable 'age' with the value 25
height = 1.75     # creates a variable 'height' with the value 1.75
is_student = True # creates a variable 'is_student' with the value True
```
### Data types
```python
string = "Hello, World!" # creates a string variable
integer = 42            # creates an integer variable
float = 3.14            # creates a float variable
boolean = True          # creates a boolean variable
```
## 2. Control Structures

### If statement
```python
if x > 0:
    print("x is positive")
elif x == 0:
    print("x is zero")
else:
    print("x is negative")
```
### For loop
```python
for i in range(10):
    print(i)
```
### While loop
```python
while x < 10:
    print(x)
    x += 1
```

## 3. Functions

### Defining a function
```python
def greet(name):
    print("Hello, " + name + "!")
```
### Calling a function
```python
greet("John")
```

## 4. Lists and Dictionaries

### Creating a list
```python
fruits = ["apple", "banana", "cherry"]
```
### Accessing list elements
```python
print(fruits[0])   # prints "apple"
print(fruits[-1])  # prints "cherry"
```
### Adding elements to a list
```python
fruits.append("orange")
fruits.insert(1, "pear")
```
### Creating a dictionary
```python
person = {"name": "John", "age": 25, "is_student": True}
```
### Accessing dictionary elements
```python
print(person["name"])    # prints "John"
print(person.get("age")) # prints 25
```
### Adding elements to a dictionary
```python
person["height"] = 1.75
person.update({"weight": 70})
```

## 5. File Handling

### Reading from a file
```python
with open("file.txt", "r") as f:
    contents = f.read()
```

### This is a cheat sheet for Python that covers the most commonly used syntax and concepts. You can use this cheat sheet as a quick reference guide when working with Python.
