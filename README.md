## Python Exceptions for Beginners

When you're just starting out with programming, there are a lot of new concepts to wrap your head around. One of those concepts is 'exceptions'. You can think of an exception as a kind of error that happens while your program is running, which, if not handled properly, can cause your program to stop abruptly.

## 1. What are Exceptions?

- You can think of an exception as a kind of error that happens while your program is running. 

- For a detailed example, check out the [01_exceptions.py](./01_exceptions.py) file.

## 2. Handling Exceptions

- Let's see how we can handle exceptions using `try...except` blocks. 
- a detailed example, check out the [02_handling_exceptions.py](./02_handling_exceptions.py) file.

##  3. Handling Different Exceptions

- You can handle different types of exceptions. This is important because not all exceptions are the same, and you might want to respond to them in different ways. 
- For a detailed example, check out the [03_handling_diff_exceptions.py](./03_handling_diff_exceptions.py) file.

## 4. Cleaning Up 

- Sometimes, you want certain pieces of code to run no matter if an exception occurs or not. You can do this with the `finally` clause. 
- For a detailed example, check out the [04_cleaning_up.py](./04_cleaning_up.py) file.

## 5. With Statement

- The `with` statement is a handy tool in Python for handling exceptions and cleanup in a cleaner and safer manner. 
- For a detailed example, check out the [05_with_statement.py](./05_with_statement.py) file.

## 6. Raising Exceptions

- You can also create your own exceptions using the `raise` keyword. 
- For a detailed example, check out the [06_raising_exceptions.py](./06_raising_exceptions.py) file.

## 7. Understanding the Cost of Exceptions

- Exceptions in Python are not meant to be used for regular flow control in your program, because raising exceptions is slower than other flow control methods. 
- if your project is small, you might use if statement to avoid exception and speed up your program.but if your project is large, then exceptions can be used. check [07_cost_of_exceptions.py](./07_cost_of_exceptions.py) file.