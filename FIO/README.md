# Readings: FileIO & Exceptions
--------

# What is the purpose of the ‘with’ statement when opening a file in Python, and how does it help manage resources while reading and writing files?


### The use of the 'with' statement in Python is a great way to simplify the management of resources that are frequently used such as file streams. It offers a concise shorthand that replaces the need for a try-catch block and guarantees that resources are closed immediately after processing. For instance, when dealing with file input and output, it is common to use the with statement to ensure that the file is properly closed after use.


# Explain the difference between the ‘read()’ and ‘readline()’ methods for file objects in Python. Provide examples of when to use each method.

### While using the read() method in Python, the entire content of the file is read and returned as a string. In contrast, the readline() method reads a single line from the file and returns it as a string. The difference between the two methods is that read() loads the entire file into memory, while readline() reads the file as a list of lines without line termination. In addition, readlines() method returns a list of all lines in a file, with each element of the list representing a line in the file.

# Briefly describe the concept of exception handling in Python. How can the ‘try’, ‘except’, and ‘finally’ blocks be used to handle exceptions and ensure proper execution of code? Provide a simple example.

### Exception handling in Python is accomplished through the try, except, and finally blocks. The code that may raise exceptions is placed in the try block, while the except block is used to catch and handle exceptions. The finally block is where you can include code that is executed regardless of whether or not an exception has been raised.

### Here's an example that shows how to use the try-except-finally blocks to handle exceptions and ensure proper execution of code:


 
```python
def read_file(filename):
    try:
        with open(filename) as f:
            contents = f.read()
            # process the file contents here
            return contents
    except:
        # handle the exception here
    finally:
        f.close()
```
