# Functions

Functions are essential for organizing and reusing code. In this section, we'll learn how to define and call functions.

### Defining Functions

A function is a reusable block of code that performs a specific task. It helps keep your code organized and makes it easier to debug and maintain.

```python
# Defining a simple function
def greet(name):
    return "Hello, " + name + "!"
```

### Calling Functions

Once you've defined a function, you can call it and pass arguments if necessary.

```python
# Calling the greet function
message = greet("Alice")
print(message)
```

### Function with Default Argument

You can provide default values for function parameters. These values are used when the caller doesn't provide a value for that parameter.

```python
# Function with default argument
def power(base, exponent=2):
    return base ** exponent

result = power(3)  # Calculates 3^2
```

### Return Statement

Functions can return values using the `return` statement. This is useful when you want to get a result from a function.

```python
def add(a, b):
    return a + b

sum = add(5, 3)  # sum will be 8
```

### Scope of Variables

Variables defined inside a function are local to that function, meaning they can't be accessed outside it.

```python
def my_function():
    x = 10
    print(x)

my_function()
print(x)  # This will result in an error
```

Understanding functions is key to writing organized and maintainable code. In the next section, we'll explore different data structures available in Python. If you're ready, let's continue!
