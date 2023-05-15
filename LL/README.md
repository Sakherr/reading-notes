## A variable’s scope determines where it can be accessed within a program. A variable’s scope is defined by where it is assigned. If a variable is assigned inside a function, it is considered local to that function and can only be accessed within that function. If a variable is assigned outside of any function, it is considered global and can be accessed anywhere in the program.

## The global keyword in Python allows you to modify a global variable from within a function. Without the global keyword, Python will create a new local variable with the same name as the global variable instead of modifying the global variable
```
my_variable = 1

def my_function():
    print(_my_variable)

my_function()

```
## The nonlocal keyword allows you to modify a variable in the nearest enclosing scope that is not the global scope. This is useful when you have nested functions and want to modify a variable in an outer function.


## Big O notation is used to describe the time complexity of an algorithm as the size of the input grows. It describes how the running time of an algorithm increases as the input size increases. Big O notation is important because it allows us to compare algorithms and choose the most efficient one for a given problem.


## To simulate a dice roll using Python, we can use the random.randint() function. This function takes two arguments: the minimum value and the maximum value. For example, to simulate a roll of a six-sided die
```
import random

number = random.randint(1, 6)
```