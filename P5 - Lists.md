# No Fluff Guide to Python - P5 - Lists

[Complete Blog Post](https://www.databasewithfun.com/2023/07/no-fluff-guide-to-python-p5-lists.html)
> To build up a library is to create a life. It's never just a random collection of books

Imagine you have a box of toys. You can put different toys in the box, like a doll, a car, and a ball. Each toy has its own place in the box. You can also take toys out of the box and play with them.

A Python array is like a box of toys, but it can only hold numbers. Each number has its own place in the array. You can also add and remove numbers from the array.

To create an array, you use the [ ] brackets. For example, the following code creates an array with the numbers 1, 2, and 3:

array = [1, 2, 3]

You can access the numbers in the array using the [ ] brackets. For example, the following code prints the first number in the array:

array = [1, 2, 3]

print(array[0])

Each item in the list is assigned an Index, starting from 0
![List Demo](./assets/list01.png)

You can access individual item using these indexes:
![List index](./assets/list02.png)

You can also change the numbers in the array using these indexes.

For example, the following code changes the first value in the array to "morning":

list1=["hello",1,4,8,"good"]
list1[0]="morning"   

New List\
["morning",1,4,8,"good"]

Update the 3rd item in the list, i.e. index 2
![List Update](./assets/list03.png)

New list looks like this:
![List Print](./assets/list04.png)

You can also add and remove numbers from the array. To add a number to the end of the array, you use the append() method. 
![List Append](./assets/list05.png)

Code looks like this:

list1=["apple","banana","grapes"]
list1.append("strawberry")\
# strawberry is added to the list
print(list1)

#Output
#['apple', 'banana', 'grapes', 'strawberry']

![List commands](./assets/list06.png)

To remove a number from the array, you use the `pop()` method. For example, the following code removes the last number from the array:

list1.pop()\
# removes the last element from the list
print(list1)

#Output
#['apple', 'banana', 'grapes']

![List add](./assets/list07.png)

### Delete vs Remove
![List delete](./assets/list08.png)

![List remove](./assets/list09.png)

#### Sorting elements:

**SORT**
-   orders the values in the lists
-   sorting is done - In Place
-   updates are done to the list itself without making another copy

![Sort](./assets/python-List-SORT.gif)

**SORTED**
- use this if the original order is important
- makes a copy of it before sorting -> by creating a new list
![Sorted](./assets/python-List-SORTED.gif)


#### Looping through all elements of a LIST:

-   use FOR loop
-   a named variable is assigned all the values one by one
    -   python creates this variable 
    -   this variable holds the actual value, rather than the index
-   VAR is assigned LIST1[0] in the first run
-   VAR is assigned LIST1[1] in the next run.. and so on
-   You can access the current element using the VAR variable.
![Loop through list](./assets/python-List-Loop.gif)

> the value of the variable used in FOR loop is not cleared after the loop is complete.

Arrays are a very useful tool for storing and manipulating data in Python. They can be used to store anything from numbers to strings to objects. 

![LIST](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgWdoefHpdoZWBTWB2dF9KXVzCPSVw3IM-jVghQsvndbb-0IF6tVGrStvIJnwcYyZuC8urjk1HlHu8JYk28vJxErsZVqIHTOnVCEXGrDXufJAA6ERxFHp67mHfV-beZ-jfXtG04x4JJabkMtY11Qa7s7QhQTwICiXklXlHUdAFu4cwk0tKYUIZXrcBHMZyZ/s2041/lists-databasewithfun.PNG)