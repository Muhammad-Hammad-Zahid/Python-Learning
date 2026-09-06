# MODULE 0: Introduction to Programming and Python
**Programming language:** A programming language is a medium we use to talk to a computer, like how we communicate with other people. A programming language allows us to write a set of instructions which deliver to a computer in the form of machine language, which only a computer can understand and use to perform given tasks.
**Python:** is a high-level language which allows humans to write instructions in a language which the humans can understand easily and that can be converted into a form which the computer can understand and use to perform the given tasks.
Thanks to its human-friendly interface, it allows us to write code in a human language, which is then converted to machine language which the computer can understand.
**Python interpreter:** An interpreter is like a language translator that converts Python, a human-readable language, into machine language that a computer can understand. The interpreter takes the program, checks the syntax, and translates it. It works in the same way that two people of different languages need a translator to communicate. In the same sense, python need interpreter to communicate with the computer
Below is an example of adding two numbers:
```python
a = int(input("Enter a Number: "))
b = int(input("Enter the Second Number: "))
c = a+b
print(f"SUM of {a} + {b} = {c}")
```
#                                                   HOW TO WRITE THE CODE
To write code, we need an environment where we can write, debug and run it, like Jupyter Notebook, Google Colab, or Visual Studio Code, etc.
As we know, Python is a very human-friendly environment which allows us to write code as if we were writing a dialogue. This makes it very convenient for us, but not for the interpreter. To make it easy to understand where each line belongs, we need to keep in mind the concept of Whitespace, Indentation, and code blocks. These concepts describe how the Python environment and the programmer interact:
**Whitespace:** is just the rules or regulations about how the environment works, like in English, how we use commas, full stops, or spaces between words to distinguish them from each other.
**Indentation:** rules we use when writing code in Python, like using enough spaces to distinguish between each block of code, for example:
```python
First_Num = int(input("Enter a Number: "))
Second_Num = int(input("Enter the Second Number: "))
Repeated_add = 0
for index in range(Second_Num):
    Repeated_add = First_Num + index
print(Repeated_add)
```
In the above figure, we can see two blocks of code one belongs to the “for loop”, and the other is a block of code outside of the loop. See how we used spaces before the instruction, to put a specific block of code under the loop control and how we use “:” to tell where the block of code belongs to the loop start.
**Block of code:** is a set of instructions combined to perform a specific task; as in the above figure, it takes two numbers and adds the first number to the value of index i until the loop ends and prints the result.

#                                                   WHY PYTHON
The Python language allows programmers to write programs like they are writing a dialogue, for example in above example we write `input("Enter a number: ")` and user reply with a number then program ask for another number and user enter again and then program takes both inputs and perform the actions it was program to take and give result to the user. This easy program-writing made Python popular and a first choice; another reason for choosing Python is the vast number of available libraries for performing complex mathematical calculations, such as derivatives. Python also allows you to build and run powerful machine learning models, perform scientific operations, handle data, and much more. This can all be done in Python with easy syntax and logic.

#                                                   WHAT’S IN THE REPOSITORY
This repository, “Python-Learning”, will teach from basic to object-oriented programming, covering basic file handling, useful data structures, and introducing important libraries, while providing mini-projects for practice and better understanding.

| Module | Topics Covered |
| :--- | :--- |
| **Module 1: Basics** | Variables • Data Types (Integer, Float, String, Boolean) • Comments • Printing Output • Taking Input • Type Conversion • Basic Operators (Arithmetic, Comparison, Logical) |
| **Module 2: Conditional Statement** | Boolean Logic • `if` Statement • `if-else` • `if-elif-else` • Nested Conditions • Practical Decision Problems |
| **Module 3: Loops** | Why Loops Exist • `while` Loop • `for` Loop • `range()` • Nested Loops • `break` • `continue` • `pass` |
| **Module 4: String** | What is a String? • Indexing • Slicing • String Methods • String Formatting • Escape Characters • Practical String Processing |
| **Module 5: Data Collection** | **Lists** (Creating, Accessing, Modifying, Methods, Traversal) • **Tuples** (Creating, Immutable Data) • **Sets** (Creating, Set Operations) • **Dictionaries** (Key-Value, Creating, Accessing, Updating, Iterating) |
| **Module 6: Function** | Why Functions Matter • Creating Functions • Parameters • Arguments • Return Values • Variable Scope • Default Arguments • Keyword Arguments • Lambda Functions |
| **Module 7: Problem Solving & Debugging** | Algorithm Basics • Flow of Execution • Tracing Code • Finding Patterns • Breaking Problems into Steps • Debugging Techniques |
| **Module 8: File Handling** | Reading Files • Writing Files • Appending Data • Working with Text Files • CSV Files • JSON Files |
| **Module 9: Error Handling** | Exceptions • `try-except` • `finally` • Raising Exceptions • Common Errors |
| **Module 10: Modules & Packages** | Importing Modules • Creating Modules • Python Standard Library • `pip` • Installing Packages • Virtual Environments |
| **Module 11: Object-Oriented Programming** | What is OOP? • Classes • Objects • Attributes • Methods • Constructors (`__init__`) • Encapsulation • Inheritance • Polymorphism • Composition |
| **Module 12: Libraries** | **NumPy** (Arrays, Operations, Math Functions) • **Pandas** (DataFrames, Reading Data, Data Cleaning, Analysis) • **Matplotlib** (Line, Bar, and Pie Charts, Visualization Basics) |
| **Module 13: Final Projects** | Student Management System • Expense Tracker • Quiz Application • Contact Book • Data Analysis Project • Library Management System |

#                                                   Where to Write: - 
There is a lot of software and notebooks available to get started with, Such as: Visual Studio Code, jupyter NOotbook, online Phyton Iterpreter(e.g., Google-Collab, Programiz, etc), etc.

#                                                   MY First Code
We will start with basic input and output. In this code, we will take a username as input and use it to write a specific output.
```python
Name = input("Enter your Name: ")
print("Hello")
print(Name)
```
**Explanation:** This is a simple Python code; it uses “input()” to take input from the user and store it in a variable called “Name”, which is then used by the output function “print()” to write the required output.
**Execution:** When Python interpreters start to execute the program, we know they read and execute the program line by line, so it first goes to first line and read it and check the syntax, it found them correct and execute the input() function which stops the entire execution and wait for the user to enter the data asked for, it only move to next line when the user write the name and press “Enter”, interpreter then save the input value in variable called “Name”, next the interpreter moves on to next line and it check the syntax again and found them correct and runs the print() function which take the variable “Name” and print in output along with other statement it was given and finally interpreter move to final to final line and again check syntax and run the print() function and ending the execution.