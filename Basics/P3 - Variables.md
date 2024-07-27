# No Fluff Guide to Python - P3 - Variables
[Complete Blog Post](https://www.databasewithfun.com/2023/07/no-fluff-guide-to-python-p2-variables.html)

![alt text](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEhXFhxIryvq-RxxwAxucFswW9DSemuudzi9HI_ap3od3T7okaxX9onWsBOBtG_iWR_h6rpXMCclAkJrB9RHyW7_KIMMsMeDwlOTgZjFW55d6Lpc46RzyQbIjuZpsBynpHdBV2p5KVTHkWze6JZsqJSNq5DCdzLr5a3VMs-vXN3FrWoig8zddTgpSrbUR_dU/s986/variables-databasewithfun.png)

### Variables

-   Variables can be created in Python using the assignment operator (=).
-   Variables can store different data types, such as strings, numbers, and boolean values.
-   Variable names should follow certain conventions, such as using lowercase letters and underscores.
-   Variables can be assigned values directly or through user input using the input() function.

In the world of programming, variables play a crucial role in storing and manipulating data. Whether you're a beginner or an experienced coder, understanding how to create variables in Python is essential. In this blog post, we will explore the basics of creating variables, their data types, naming conventions, and ways to assign values. So let's dive in!

#### Creating Variables:

In Python, creating variables is a simple process that involves using the assignment operator (=). Let's take a look at an example:

```python
name = "Ram"
age = 25
is_student = True
```

In the above code snippet, we created three variables:`name`,`age`, and `is_student`. The variable `name`stores a string value "Ram," `age`stores an integer value 25, and `is_student`stores a boolean value True.

#### Data Types in Variables:

Python is a dynamically typed language, which means variables can store different data types. Some commonly used data types include:

1.  Strings: Used to represent textual data. It is enclosed in either single ('') or double quotes ("").
2.  Numbers: Representing numerical values, which can be further classified into integers and floating-point numbers.
3.  Boolean: Represents either True or False values, which are used for logical operations.

#### Naming Conventions:

While creating variables, it's important to follow certain naming conventions to write clean and readable code. Here are some guidelines for naming variables in Python:

1.  Variable names should start with a letter or an underscore (_) character.
2.  They can contain letters, digits, and underscores.
3.  Variable names are case-sensitive, meaning `age` and `Age` are treated as two different variables.
4.  It is recommended to use lowercase letters and underscores for better readability. For example, `my_variable` instead of `MyVariable`.

#### Assigning Values to Variables:

Variables can be assigned values directly or through user input using the `input()` function. Let's see how this works:

Direct Assignment:
```python
name = "Ram"
age = 25
```

User Input:
```python
name = input("Enter your name: ")
age = int(input("Enter your age: "))
```

In this code, the `input()` function prompts the user to enter their name and age. The `int()` function is used to convert the inputted age from a string to an integer data type.