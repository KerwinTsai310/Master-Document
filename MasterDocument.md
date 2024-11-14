# Python Beginner Guide

Welcome to the **Python Beginner Guide**! This is a simple introduction to Python, perfect for beginners who want to learn the basics of coding. This guide covers comments, variables, data types, printing, and more.

## Requirements

To follow this guide, you need:
- Access to [GitHub Codespaces](https://github.com/features/codespaces) (where you can write and run Python code online!)

## Vocabulary
- Input: Input is the code you put into the codespace. It has lines on the side stating what line of code you are on. You will see these later in the document as **Code Blocks**.
- Output: Output is what the Input does. You will see this later in the document as a dropdown that says **Output**

## Topics Covered

1. **Comments**
2. **Variables**
3. **Data Types**
4. **Printing**
5. **Input**
6. **Changing Data Types**
7. **Strings**

## Usage

You can use this guide as a reference for Python basics. Each section has examples to help you understand.

### 1. Comments

**Comments** are notes in your code that Python ignores. They help explain what your code does.

```python
# This is a comment explaining the code below
print("Hello, World!") 
```

<details>
<summary>Output</summary>

```
Hello, World!
```
</details>


### 2. Variables

**Variables** are like containers that hold values. You can use variables to store things like numbers, words, or other types of data, and you can change these values later in your code.

```python
name = "Alice"    # This variable stores the name "Alice"
age = 12          # This variable stores the number 12
is_student = True # This variable stores the value True

# Printing the values of the variables
print(name, age, is_student)  # This will print: Alice 12 True
```

<details>
<summary>Output</summary>

```
Alice 12 True
```
</details>


### 3. Data Types

#### Basic Types
- **String (str):** Text data, like `"hello"` or `'world'`
- **Integer (int):** Whole numbers, like `42` or `-17`
- **Float:** Decimal numbers, like `3.14` or `-0.001`
- **Complex:** Complex numbers, like `3+4j`
- **Boolean (bool):** True or False values

#### Collection Types
- **List:** Ordered, changeable sequences `[1, 2, 3]`
- **Tuple:** Ordered, unchangeable sequences `(1, 2, 3)`
- **Set:** Unordered collection of unique items `{1, 2, 3}`
- **Dictionary (dict):** Key-value pairs `{"name": "Alice", "age": 12}`

```python
# Basic Types
text = "Hello"           # String
number = 42              # Integer
decimal = 3.14           # Float
complex_num = 3 + 4j     # Complex
is_active = True         # Boolean

# Collection Types
my_list = [1, 2, 3]                    # List
my_tuple = (1, 2, 3)                   # Tuple
my_set = {1, 2, 3}                     # Set
my_dict = {"name": "Alice", "age": 12} # Dictionary

# Print types of all variables
print("Basic Types:")
print(f"String: {type(text)}")
print(f"Integer: {type(number)}")
print(f"Float: {type(decimal)}")
print(f"Complex: {type(complex_num)}")
print(f"Boolean: {type(is_active)}")
# We will be explaining the f after the print soon
print("\nCollection Types:")
print(f"List: {type(my_list)}")
print(f"Tuple: {type(my_tuple)}")
print(f"Set: {type(my_set)}")
print(f"Dictionary: {type(my_dict)}")
```

<details>
<summary>Output</summary>
  
```
Basic Types:
String: <class 'str'>
Integer: <class 'int'>
Float: <class 'float'>
Complex: <class 'complex'>
Boolean: <class 'bool'>

Collection Types:
List: <class 'list'>
Tuple: <class 'tuple'>
Set: <class 'set'>
Dictionary: <class 'dict'>
```
</details>
</details>


### 4. Printing

#### Basic Print
The `print()` function is used to output text to the console:
```python
# Simple print statement
print("Hello, World!")

# Print multiple items
print("Hello", "World", "!")

# Print with numbers
print("I am", 25, "years old")
```

<details>
<summary>Output</summary>
  
```
Hello, World!
Hello World !
I am 25 years old
```
</details>

#### Print Formatting
Different ways to format your print statements:

##### Using F-strings (Recommended)
```python
name = "Alice"
age = 12
print(f"My name is {name} and I am {age} years old")

# F-strings with expressions
price = 10
quantity = 3
print(f"Total cost: ${price * quantity}")
```

<details>
<summary>Output</summary>
  
```
My name is Alice and I am 12 years old
Total cost: $30
```
</details>

#### Special Characters
Print statements can include special characters:
```python
# New line
print("Line 1\nLine 2")

# Tab
print("Name:\tAlice")

# Print without newline
print("I", end=" am ") # You can change this " am " to anything you want the string to end with.
print("Amazing!")
```

<details>
<summary>Output</summary>
  
```
Line 1
Line 2
Name:	Alice
I am Amazing!
```
</details>
