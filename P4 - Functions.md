# No Fluff Guide to Python - P4 - Functions

[Complete Blog Post](https://www.databasewithfun.com/2023/07/no-fluff-guide-to-python-p4-functions.html)
> Functions in programming: the superheroes that save you from repeating yourself, one line at a time

### **Functions**

-   Functions allow you to group a set of code that runs when called.
-   The def keyword is used to define a function.
-   Indentation is important in Python to define the code within a function.
-   Functions can have parameters, which are variables that hold the values passed to the function.
-   The return statement is used to specify the value returned by the function.

![Function and actions items](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEiQeOoWE9wOpOYbDI0prsg30gKFPtaq_23eWkURvZL9V6EXD2gDZEUPMr1C5W9zoPJBBeRZ60MHKtMUzxLiGanJmgQ_Nr9eZK_bevGTQtyHUc0nmmD4CaZlCOMFycinXnCyCBykR3Thogg5NvRx71yyCW9UvrIYad8ZCfl1CxZY8usQGTiuCTcsFWDZ1syl/s724/functions-databasewithfun.png)

Functions in Python are like superheroes that come to the rescue when you need to execute a set of code repeatedly. They not only make your code more organized but also allow you to add a touch of humor to your programming experience. In this blog post, we will dive into the world of Python functions, understanding their syntax, indentation rules, parameters, and the almighty return statement. So, fasten your seatbelts and get ready for a fun-filled coding adventure!

#### Defining Functions:

In Python, you can define functions using the `def` keyword. Let's take a look at a funny example:
```python
def greet():
    print("Why don't scientists trust atoms?")
    print("Because they make up everything!")
```

In the above code snippet, we defined a function called `greet()` that prints out a hilarious science joke. Remember, indentation is crucial in Python, so make sure to indent the code within the function using four spaces or a tab.

#### Adding Parameters:

Functions can have parameters, which are like secret agents that bring in external values for your function to work with. Here's an amusing example:
```python
def knock_knock(joke_name):
    print("Knock, knock!")
    print("Who's there?")
    print(joke_name + " who?")
    print("You must be joking!")
```

 In this code, we defined a function called `knock_knock()` that takes a parameter `joke_name`. The function then prints out a classic knock-knock joke by combining the `joke_name` with the punchline.

#### The Return Statement:

The `return` statement is like a magic trick that allows your function to produce a result and share it with the outside world. Brace yourself for a hilarious example:
```python
def add_numbers(num1, num2):
    result = num1 + num2
    return "The sum of " + str(num1) + " and " + str(num2) + " is " + str(result) + ". But I won't give you the answer directly. You must solve it yourself!"
```

 In this code, the `add_numbers()` function takes two parameters, `num1` and `num2`, adds them together, and creates a funny message that encourages the user to solve the addition problem themselves. The result is then returned