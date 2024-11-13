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

Python has different types of data that you can use in your code. Here are the most common types:

- **String (str):** Text, like `"hello"`
- **Integer (int):** Whole numbers, like `12`
- **Float:** Decimal numbers, like `3.14`
- **Boolean (bool):** True or False values

```python
name = "Alice"    # String (str): Stores text
age = 12          # Integer (int): Stores a whole number
height = 5.4      # Float: Stores a decimal number
is_student = True # Boolean (bool): Stores a True or False value

# Printing the types of the variables
print(type(name))   # This will print: <class 'str'>
print(type(age))    # This will print: <class 'int'>
print(type(height)) # This will print: <class 'float'>
print(type(is_student)) # This will print: <class 'bool'>
```
<details>
<summary>Output</summary>

```
<class 'str'>
<class 'int'>
<class 'float'>
<class 'bool'>
```
</details>

