# Assignment 1

## 1)Who developed python programming language?


- Python was Developed by Guido van Rossum in 1980s.
- He was the lead developer and chief decision-maker of Python until he stepped down in 2018

## 2)Which type of programming does Python support?

Python is known for its flexibility and supports multiple programming paradigms. Here are the main types of programming supported by Python:
1. Object-Oriented Programming (OOP)

2. Structured Programming

3. Functional Programming


## 3)Is Python Case sensitive when dealing with identifiers?

**Yes**, Python is case sensitive in case of identifiers.

## 4)What is the correct extension of the Python file?


#### **.py:**
- This is the standard extension for regular Python source code files.
- It contains raw Python code that can be directly executed by the Python interpreter.
- .py files are typically used for writing functions, classes, scripts, and modules.


#### .ipynb
- It stands for "Interactive Python Notebook".
- It is a file format used for writing Jupyter Notebooks.
- Jupyter Notebooks are a popular tool for data analysis and visualization in Python.

## 5)Is Python code compiled or interpreted?

### Short Answer:
According to the official Python documentation, Python is an interpreted language. 

### Detailed Answer:
 **Python is often considered an interpreted language, but it technically involves both compilation and interpretation. Here's how it works:**

1. **Compilation to Bytecode:**
   - When you run a Python script, the Python interpreter first compiles your code into an intermediate format called bytecode.
   - This bytecode is stored in .pyc files for future use.
   - Bytecode is platform-independent, so it can run on different operating systems without recompilation.

2. **Interpretation of Bytecode:**
   - The Python virtual machine (PVM) then interprets the bytecode line by line, executing the instructions on your computer's hardware.
   - The PVM is responsible for managing memory, calling functions, and interacting with the operating system.

**Key Points:**

- The compilation step is often hidden from the user, making Python feel like a purely interpreted language.
- This compilation to bytecode is a crucial optimization that makes Python faster than purely interpreted languages.
- The Python interpreter itself is written in C, which provides performance benefits.
- Alternative Python implementations, like PyPy, use Just-in-Time (JIT) compilation for further speed improvements.

**In essence:**

- Python code is initially compiled into bytecode, but this bytecode is then interpreted by the PVM, giving Python characteristics of both compiled and interpreted languages.
- This hybrid approach offers a balance between flexibility and performance, making Python suitable for a wide range of development tasks.

## 6)Name a few blocks of code used to define in Python language?


Blocks of code in Python are groups of statements that are executed as a unit. They are usually nested inside another syntactical element, such as a function, a class, or a control structure.

Here are a few common blocks of code used in Python:
- **Function Definition:**
  - A block of code that defines a reusable function with a specific name and set of parameters.
  - Example:
    ```python
    def my_function(parameter1, parameter2):
        # Code block for the function
        print(parameter1 + parameter2)
    ```

- **For Loop:**
  - A block of code that iterates over a sequence of elements, executing a set of statements for each element.
  - Example:
    ```python
    for item in my_list:
        # Code block for the loop
        print(item)
    ```

- **While Loop:**
    - A block of code that repeatedly executes a set of statements as long as a specified condition is true.
    - Example:
        ```python
        while condition:
            # Code block for the loop
            print("Condition is true")
        ```

## 7)State a character used to give single-line comments in Python?

The character "#" (hash or pound symbol) is used to create single-line comments in Python. Any text following the "#" symbol on the same line is treated as a comment and is ignored by the Python interpreter.

## 8)Mention functions which can help us to find the version of python that we are currently working on?

To find the version of Python that we are currently working on, we can use the following functions:

1. **sys.version:**
   - The `sys` module provides system-specific parameters and functions, including version information.
   - Example:
     ```python
     import sys
     print(sys.version)
     ```

2. **platform.python_version():**
    - The `platform` module provides a portable way of using operating system-dependent functionality, including Python version information.
    - Example:
      ```python
      import platform
      print(platform.python_version())
      ```

3. **Python Version Command:**
    - We can also use the Python version command in the terminal or command prompt to check the version of Python installed on our system.
    - Example:
      ```
      python --version
      ```

## 9)Python supports the creation of anonymous functions at runtime, using a construct called?

Python supports the creation of anonymous functions at runtime using a construct called "lambda" functions.

**Lambda Functions:**
- Lambda functions are small, anonymous functions that can have any number of parameters but can only have one expression.
- They are defined using the `lambda` keyword, followed by a comma-separated list of parameters, a colon, and the expression to be evaluated.
- Example:
  ```python
  add = lambda x, y: x + y
  print(add(3, 5))  # Output: 8
  ```


## 10. What does pip stand for python?

According to the creator of pip, Ian Bicking, the name is a recursive acronym for “Pip Installs Packages” or “Pip Installs Python”

## 11)Mention a few built-in functions in python?

Here are names of few built-in functions in Python:
- **print()**
- **len()**
- **input()**
- **range()**
- **type()**
- **int()**
- **str()**
- **float()**

## 12)What is the maximum length of an identifier in Python?

According to the official Python style guide, PEP 8, the maximum length of an identifier is 79 characters. This is to ensure that the code is consistent and fits within the standard display size.


## 13)What are the benefits of using Python?

These are the benefits of using Python:
- **Readability and Simplicity:**
  - Python code is easy to read and understand, making it accessible to beginners and experienced developers alike.
  - Its clean and consistent syntax reduces the cost of program maintenance and development.


- **Versatility and Flexibility:**
    - Python supports multiple programming paradigms, including object-oriented, structured, and functional programming.
    - It can be used for web development, data analysis, artificial intelligence, scientific computing, and more.



- **Large Standard Library:**
    - Python comes with a large standard library that provides tools and modules for a wide range of tasks, from working with files to implementing web servers.


- **Community and Ecosystem:**
    - Python has a large and active community of developers who contribute to open-source projects, libraries, and frameworks.
    - This ecosystem provides a wealth of resources and support for Python developers.

## 14)How is memory managed in Python?


Memory management in Python is the process of allocating and deallocating memory for Python objects and data structures. Python has a built-in memory manager that handles this process automatically. Here's how memory management works in Python:

Python uses a private heap to store all its objects and data structures. The heap is managed by the Python memory manager, which allocates memory blocks to Python objects as needed. The memory manager also keeps track of the reference counts of each object, which indicate how many variables or other objects point to that object.

When an object's reference count becomes zero, it means that the object is no longer accessible or needed by the program. The memory manager then deallocates the memory block occupied by that object and makes it available for other objects¹². This process is called garbage collection, and it helps to prevent memory leaks and fragmentation.

## 15)How to install Python on Windows and set path variables?


Skippiing this question as it is not relevant to the assignment.

## 16)Is indentation required in python?

Yes, indentation is required in Python. Python uses indentation to define the scope and structure of code blocks, such as functions, loops, and conditional statements.