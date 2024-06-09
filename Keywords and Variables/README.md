# Python Keywords and Variables

## Keywords

Python keywords are reserved words that have special meaning and cannot be used as variable names, function names, or any other identifiers. Here is a list of Python keywords:

| Keyword   | Description                                          |
|-----------|------------------------------------------------------|
| `False`   | Boolean value representing false                     |
| `None`    | Represents a null value                              |
| `True`    | Boolean value representing true                      |
| `and`     | Logical and                                          |
| `as`      | Used to create an alias                              |
| `assert`  | For debugging                                        |
| `async`   | For asynchronous operations                          |
| `await`   | To wait for an async operation to complete           |
| `break`   | To break out of a loop                               |
| `class`   | To define a class                                    |
| `continue`| To continue to the next iteration of a loop          |
| `def`     | To define a function                                 |
| `del`     | To delete an object                                  |
| `elif`    | Used in conditional statements, same as else if      |
| `else`    | Used in conditional statements                       |
| `except`  | Used with exceptions, what to do when an exception occurs |
| `finally` | Used with exceptions, a block of code that will be executed no matter what |
| `for`     | To create a for loop                                 |
| `from`    | To import specific parts of a module                 |
| `global`  | To declare a global variable                         |
| `if`      | To make a conditional statement                      |
| `import`  | To import a module                                   |
| `in`      | To check if a value is present in a list, tuple, etc.|
| `is`      | To test object identity                              |
| `lambda`  | To create an anonymous function                      |
| `nonlocal`| To declare a non-local variable                      |
| `not`     | Logical not                                          |
| `or`      | Logical or                                           |
| `pass`    | A null statement, a statement that will do nothing   |
| `raise`   | To raise an exception                                |
| `return`  | To exit a function and return a value                |
| `try`     | To make a try...except statement                     |
| `while`   | To create a while loop                               |
| `with`    | Used to simplify exception handling                  |
| `yield`   | To end a function, returning a generator             |

## Variables

Variables in Python are used to store data that can be referenced and manipulated in a program. A variable is created the moment you first assign a value to it.

### Variable Naming Rules

1. Variable names must start with a letter or the underscore character.
2. Variable names cannot start with a number.
3. Variable names can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ ).
4. Variable names are case-sensitive (age, Age, and AGE are three different variables).

### Examples

#### Creating and Using Variables

```
# Integer variable
x = 5
print(x)  # Output: 5

# Float variable
y = 3.14
print(y)  # Output: 3.14

# String variable
name = "Alice"
print(name)  # Output: Alice

# Boolean variable
is_active = True
print(is_active)  # Output: True

# Multiple variables
a, b, c = 1, 2, 3
print(a, b, c)  # Output: 1 2 3

# Reassigning variables
x = 10
print(x)  # Output: 10

# Using variables in expressions
result = x + y
print(result)  # Output: 13.14
```
#### Global and Local Variables
```
# Global variable
global_var = "I am global"

def my_function():
    # Local variable
    local_var = "I am local"
    print(local_var)  # Output: I am local
    print(global_var)  # Output: I am global

my_function()
print(global_var)  # Output: I am global

# Uncommenting the next line would raise an error because local_var is not accessible outside the function
# print(local_var)  # NameError: name 'local_var' is not defined
```
