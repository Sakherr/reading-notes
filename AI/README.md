## What is the purpose of dunder methods in Python? Provide an example of a commonly used dunder method.

### Customize the way objects are printed to the console
### Customize the way objects are compared to each other
### Customize the way objects are added, subtracted, multiplied, divided, and so on
### Customize the way objects are called

### Dunder methods, also known as magic methods, are special methods in Python that start and end with two underscores. They are used to customize the behavior of built-in operators and functions.



## The __init__() method is a dunder method that is called when an object is created. The __init__() method is used to initialize the object's attributes.

## For example, the following code defines a class called Point and overrides the __init__() method:

```
class Point:
    def __init__(self, x, y):
        self.x = x
        self.y = y
```



## In the video “AI Guru makes $238,800 with misleading paid course,” what was the main ethical issue raised concerning the use of developers’ work, and how might this have been avoided?

### The main ethical issue raised in the video is that the AI Guru was using developers' work without their permission. The AI Guru took code from GitHub repositories and used it in his paid course without giving any credit to the original developers. This is a clear violation of copyright law and it is also unethical.


### The AI Guru could have avoided this ethical issue by getting permission from the original developers before using their code. He could have also given credit to the original developers in his course. This would have been the ethical thing to do and it would have also avoided any legal problems.


## Describe the Python statistics module and give an example of a function within the module that can be used to perform a common statistical operation.


### The Python statistics module provides a number of functions for calculating mathematical statistics of numeric data. Some of the most commonly used functions in the statistics module include:

1-mean(): Calculates the mean of a dataset.
2-median(): Calculates the median of a dataset.
3-mode(): Calculates the mode of a dataset.
4-standard_deviation(): Calculates the 5-standard deviation of a dataset.
6-variance(): Calculates the variance of a dataset.

example 
```
import statistics

dataset = [1, 2, 3, 3, 4]

mean = statistics.mean(dataset)
median = statistics.median(dataset)
mode = statistics.mode(dataset)

print("Mean:", mean)
print("Median:", median)
print("Mode:", mode)
```