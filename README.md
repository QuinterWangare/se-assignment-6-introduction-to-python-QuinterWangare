[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15307392&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.

   Python is a high-level programming language. It uses a common English language for coding that is more understandable to the user. Because of this python execution is a little bit slower than low-level languages. It makes it a user-friendly language and adds an important feature of python.
   Key Python Features:
   Simple to learn and, because of its flexible syntax, it can be used to build nearly any software application.
   Easy to understand.
   Python is an interpreted language, which means that, unlike other programming language, its code gets executed line by line rather than all at once.
   Python is an open source as well as free programming language.
   It has extensive libraries.
   It is a versatile language.

   Use cases:
   Web Development: Using frameworks like Django and Flask.
   Data Science: Libraries like Pandas, NumPy, and Matplotlib.
   Machine Learning: Libraries such as TensorFlow and scikit-learn.
   Automation: Scripting and automating tasks with tools like Selenium and BeautifulSoup.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.

   Python installation steps:
   a. Visit python.org and download the latest Python installer.
   b. Execute the installer and check "Add Python to PATH".
   c. Verify installation: Open a terminal or command prompt. Run `python --version`.

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.

   Hello World Python Program:
   print("Hello, World!")

   Explanation:
   In the above program, I have used the built-in `print()` function to print the string `Hello, world!` to the console.
   `"Hello, World!"`: A string argument passed to the print() function.

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.

   Basic Data Types:
   int: Integer numbers.
   float: Floating-point numbers.
   str: Strings of text.
   bool: Boolean values (True or False).
   list: Ordered collection of items.
   dict: Collection of key-value pairs.

   Script:
   # Integer
   x = 10
   print(type(x))  # <class 'int'>

   # Float
   y = 3.14
   print(type(y))  # <class 'float'>

   # String
   name = "Alice"
   print(type(name))  # <class 'str'>

   # Boolean
   is_active = True
   print(type(is_active))  # <class 'bool'>

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.

   Loops and conditional statements are powerful constructs that allow programmers to automate repetitive tasks and control the flow of their programs based on certain conditions.
   Conditional statements with the proper comparison and boolean operators allow the creation of alternate execution paths in the code.
   A loop is syntax structure that repeats all the statements within the loop until the exit condition is met.

   Examples:
   If-else Statement:
   age = 18
   if age >= 18:
      print("You are an adult.")
   else:
      print("You are a minor.")

    For Loop:
    # for loop
   for i in range(5):
    print(i)

   # while loop
   count = 0
   while count < 5:
    print(count)
    count += 1


6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.

   Python Functions is a block of statements that return the specific task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again.

   Example Function:
   def add(a, b):
    return a + b

   # Calling the function
   result = add(3, 5)
   print(result)  # Output: 8

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.

   Lists are ordered collections of items, whereas the dictionary is an unordered collection of data in a key: value pair form. 

   Script:
   # List
   numbers = [1, 2, 3, 4, 5]
   numbers.append(6)
   print(numbers)  # [1, 2, 3, 4, 5, 6]

   # Dictionary
   person = {"name": "Alice", "age": 25}
   person["email"] = "alice@example.com"
   print(person)  # {'name': 'Alice', 'age': 25, 'email': 'alice@example.com'}

8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.

   In Python, Exception handling allows the program to continue to execute even if an error occurs.

   Example:
   try: 
   numerator = 10 
   denominator = 0 
   result = numerator/denominator 
   print(result) except: print("Error: Denominator cannot be 0.") finally: print("This is finally block.")

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.

   A module is a single file containing Python code, whereas a package is a collection of modules that are organized in a directory hierarchy.

   Importing:
   Use the import keyword followed by the name of the module or file where the class is defined, and then access the class using the dot syntax.

   Example:
   # Using the math module
   result = math.sqrt(16)
   print(result)  # Output: 4.0

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.

   How to read from and write to files in Python:
    Read Only ('r’): This mode opens the text files for reading only.
    Read and Write ('r+’): This method opens the file for both reading and writing.
    Write Only ('w’): This mode opens the file for writing only. 
    Write and Read ('w+’): This mode opens the file for both reading and  writing. 
    Append Only ('a’): This mode allows the file to be opened for writing. 
    Append and Read (‘a+’): Using this method, you can read and write in the file. 
    Example:
    Reading from:
    with open('example.txt', 'r') as file:
    content = file.read()
    print(content)

    Writing to:
    books = ["Book 1", "Book 2", "Book 3"]
    with open('output.txt', 'w') as file:
    for line in lines:
        file.write(book + "\n")



# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 28th June 2024.


