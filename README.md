# Python

## Day 1: Introduction to Python, Installation, and Configuration
- Introduction to Python and its role in DevOps.
- Installing Python and setting up a development environment.
- Writing your first Python program.

## Day 2: Intro to Datatypes, Working with Strings and Numbers
- String data type in Python.
- String manipulation and formatting.
- Regular expressions for text processing.
- Numeric data types in Python (int, float).
 
## Day 3: Keywords and Variables
- Understanding variables in Python.
- Variable scope and lifetime.
- Variable naming conventions and best practices.
- Practice exercises and examples:
  - Example: Using variables to store and manipulate configuration data in a DevOps context.

## Day 4: Functions, Modules and Packages
- What are differences between function, modules and packages ?
- How to import a package ?
- What are Python workspaces ?

## Day 5: Environment Variables and Command Line Arguments
- Reading and writing environment variables in Python.
- Using the os and dotenv modules.
- Securing sensitive information in environment variables.
- Handling command line arguments in Python.
- Practice exercises and examples:
  - Example: Developing a Python script that accepts command line arguments to customize DevOps automation tasks.

## Day 6: Operators
- Introduction to operators in Python.
- Arithmetic, comparison, and logical operators.
- Bitwise and assignment operators.
- Practice exercises and examples:
  - Example: Using operators to perform calculations and comparisons in a DevOps script.

## Day 7: Conditional Handling using if, elif and else
- Conditional statements (if, elif, else).
- Practice exercises and examples:

## Day 8: Working with Lists (Part 1)
- Understanding lists and list data structure.
- List manipulation and common list operations.
- Practice exercises and examples:
  - Example: Writing a script to manage a list of user accounts in a DevOps environment.
  
## Day 9: Loops
- Loops in Python (for and while).
- Loop control statements (break, continue).
- Practice exercises and examples:
  - Example: Automating a log file analysis with a loop to find errors.

## Day 10: Working with Lists (Part 2)
- List comprehensions.
- Nested lists and advanced list operations.
- Practice exercises and examples:
  - Example: Print list of files in the list of folders provided

## Day 11: Working with Dictionaries and Sets (Project-1)
- Dictionaries and key-value pairs.
- Sets and set operations.
- Practice exercises and examples:
  - Example: Managing a dictionary of server configurations and optimizing retrieval.

## Day 12: Python Tasks for DevOps (Part 1) - File Operations (Project-2)
- Introduction to File Operations and Boto3.
- Automating File operations.
- Practice exercises and examples:
  - Example: Update a server resources in the server.conf file up on external notification.

## Day 13: Python Tasks for DevOps (Part 2) (Project-3)
- Using Fabric for remote task automation.
- AWS automation with Boto3.
- Managing EC2 instances, S3 buckets, and more.
- Practice exercises and examples:
  - Example: Creating a aws script for deploying applications to remote servers.
  - 


# Lists

```
# Lists are mutual that we can change values
nums = [10,17,56,89,11,20] # eliments/ Index values  [0,1,2,3,4,5,6]
print(nums)

#print specific eliment
print (nums[5])

#print some from specific eliment to end
print ("print some from specific eliment to end")
print (nums[3:])

### print float string and intiger
values = [10.5, 'prashanthGR', 100]
print(values)

# list of lists
mil = [nums, values]
print(mil)

# Operates in List

nums.append(1000) # apend value to list
print (nums)

nums.insert(3,105) # Inset value at 3 index / inbetween of list
print (nums)

nums.remove(1000) # remove value from list , value is 1000print (nums)
print (nums)

nums.pop(3) # remove value from list Using its Inedex value
print(nums)

nums.pop() # remove last value from the list
print(nums)

del nums[3:] # delete multiple valuse starting from 3rd Index
print(nums)

nums.extend ([2000,4000,500]) # append multiple values to the list
print(nums)


#List Inbuilt Fuctions

print (nums.sort())  # sort valumes from list

print (min(nums)) # find minimum value from list

print (max(nums)) # find maximum value from list

print (sum(nums)) # find sum of total from the list

print (nums.sort())
```
