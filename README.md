[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/WfNmjXUk)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15389719&assignment_repo_type=AssignmentRepo)
# SE-Assignment-6
 Assignment: Introduction to Python
Instructions:
Answer the following questions based on your understanding of Python programming. Provide detailed explanations and examples where appropriate.

 Questions:

1. Python Basics:
   - What is Python, and what are some of its key features that make it popular among developers? Provide examples of use cases where Python is particularly effective.
   Python is a programming language that is used for code readability.
   some of the key features of python that make it popular among developers include:
   1.It is a powerful,flexible and easy language to use
   2.It has a generalized, high level programming language
   3.It has small programs compared to other programming languages such as Java and C+
Examples of cases where python is particulary effective include:
1.Python is effective in enterprise and business appilications where it is used in data analysis and automation.
2.Python is effectively applied in graphics, games and scientific computations
3.Its effective use on web frameworks and appilications such as Django 
4.Python is largely used in the geneal software development
5.Its effective use in the development of other programming languages make it popular among dvelopers. This plays a key role in language development
6. It is used in scripting and the automation of tasks such as web scrapping and in the automation of complex mathematical operations.

2. Installing Python:
   - Describe the steps to install Python on your operating system (Windows, macOS, or Linux). Include how to verify the installation and set up a virtual environment.
   Steps
   1. Before the installation of python, verify your computers system requirements on your windows machine.
   2. Download the python installer from the official website of python![python official website](image.png)
   3. Locate the downloaded installer file and double click to start the installation process. Once prompted by the user account control to allow installation, click on yes to proceed.
   4. Customize on the installation.![python installation](image-1.png)
   There are anumber of options presented such as installation of the python version for all users
Associate files with Python (requires the ‘py’ launcher)
Creation of shortcuts for installed applications
Addition Python to environment variables
Precompile standard library
Download debugging symbols
Download debug binaries (requires VS 2017 or later)
   5. After selecting all the desired settings click on install to start the installation process
   6. Once the installation process is complete, we can verify the python version installed![python version](image-2.png), Click on git bash and run the command.
   7. In setting up a vertiual environment. Create a directory and run the command ![virtual environment](image-3.png) . To activate the virtual environment,run the command ![activation of the virtual environment](image-4.png)

3. Python Syntax and Semantics:
   - Write a simple Python program that prints "Hello, World!" to the console. Explain the basic syntax elements used in the program.
   Using python, we can employ the print()function 
   print("Hello, World!")
   Using the code, we call the print() function with the string "Hello, World!" as its argument. Running the code, will display the message on the console. 

4. Data Types and Variables:
   - List and describe the basic data types in Python. Write a short script that demonstrates how to create and use variables of different data types.
   Data types describe the type of data to be stored in a variable.The data types include, numeric, string, sequence,mapping, bootlean and set.For example, in python, to create numerical data, we employ the int, float and complex classes.
   Use the type function() to identify which class a variable belongs to.![numerical example input](image-18.png), output![numerical data](image-19.png)
   In python, string is a sequence of characters represented by either single or double quotes.To create a string data type, for example one can use the name and message values![example](image-20.png). The output can be read as![output of string data](image-21.png)
   For set data types in python, the set holds unique data collections that cannot be duplicated. One can create sets by placing elements inside {} separated by commas![example of set data type input](image-22.png). On this data set the output is shown as ![output](image-23.png)

5. Control Structures:
   - Explain the use of conditional statements and loops in Python. Provide examples of an `if-else` statement and a `for` loop.
   Conditional statements(if,else and elif) in python are essential programming constructs that allow one to control the flow of a program based on the conditions specified. In python, the if-else statement is used when:
   If the condition is true, the code block indented below the if statement will be executed, and the code block indented below the else statement will be skipped. 
   If the condition is false, the code block indented below the else statement will be executed, and the code block indented below the if statement will be skipped.
   An example of if-else statement ![to check whether a number is positive or negative](image-14.png) This is to check if num is greater than 0. If it is, the message "The number is positive." is printed. If it is not (that is, num is negative or zero), the message "The number is negative." is printed.![output](image-15.png)
   Loops in python are used for iterating over a sequence, which may be a list,a set, a dictionary, or a string.With the 'for' loop we can execute a set of statements once for each item in a list![example](image-16.png)![output](image-17.png)

6. Functions in Python:
   - What are functions in Python, and why are they useful? Write a Python function that takes two arguments and returns their sum. Include an example of how to call this function.
   Functions in python are reusable blocks of code that perform specific tasks. One can organize a program in a manner that is modular, readable and esier to maintain. For example a python function that takes two arguments and returns their sum![example 1](image-12.png).To call the function,![output](image-13.png), which is then printed to the console.

7. Lists and Dictionaries:
   - Describe the differences between lists and dictionaries in Python. Write a script that creates a list of numbers and a dictionary with some key-value pairs, then demonstrates basic operations on both.
   Lists in Python are ordered collections of items in which each item is assigned to an index value starting from 0 whereas a dictionary is an unordered collection of data in the key(value pair form). There are several  other differences between lists and dictionaries in python.
   A list has elements that can be accessedusing the index whereas in the dictionary, elemnts can be accessed using keys.
   A list allows for duplication of items whereas a dictionary does not allow duplication of keys
   A list has the capacity to store any data type whereas a dictionary in python can be of any imutable data type, and values can be of any data type
   Lists can perform  faster for ordered operations like sorting, whereas dictionaries perform faster for lookup operations.
   To create a list in python, use square brackets[]![list of numbers](image-10.png)
   To create a dictionary in python, use{} to separate key and value![dictionary](image-11.png)


8. Exception Handling:
   - What is exception handling in Python? Provide an example of how to use `try`, `except`, and `finally` blocks to handle errors in a Python script.
   Exception handling in python allows programs to run inspite of errors in the code or invalid input of the user.For example !['try', 'except' block](image-8.png). The program run under the 'try' statement, with'x' undefined variable, will run the 'except' statement and print a warning.
   In normal circumstances, the undefined 'x'would be thrown as an error and the execution of the code stopped.
   'Finally'  will always be executed,  whether the 'try' block raises an error or not:!['finally' block](image-9.png).This is useful in close objects and clean up resources.

9. Modules and Packages:
   - Explain the concepts of modules and packages in Python. How can you import and use a module in your script? Provide an example using the `math` module.
   A module is a single file that contains Python code in the form of functions, executable statements, variables, and classes whereas a package is a collection of modules organized in a directory
   For one to create a module, simply create a .py file with Python code and save it in the same directory as your Python script.Proceed to import and use functions, classes, or variables from the module using the import statement
   math: provides a wide range of mathematical functions and constants (useful when performing various mathematical operations in our code).For example;![math module](image-7.png)

10. File I/O:
    - How do you read from and write to files in Python? Write a script that reads the content of a file and prints it to the console, and another script that writes a list of strings to a file.
    For one to rwead an write to files in python, use  the open function() with the mode 'r' to read from the file. The read() method is consequently used to read files, that are printed to the console.![reads content](image-6.png)
    For a user to write a list of strings to a file, use the open function() with the mode 'w'![list of strings ](image-5.png). Each string is written to the file using the write()method

    References
    https://www.dataquest.io
    https://www.python.org
    https://www.geeksforgeeks.org
    https://phoenixnap.com
    https://kinsta.com/knowledgebase/install-python/
    https://www.w3schools.com/python
    https://www.datacamp.com/tutorial


# Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide code snippets or complete scripts where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by [due date].


