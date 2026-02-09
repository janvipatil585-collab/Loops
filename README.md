# Loops
programs on loops in python,

Loops in Python
In Python, loops are used to execute a block of code repeatedly until a certain condition is met or for each item in a sequence. They help reduce code repetition and make programs more efficient.

Types of Loops in Python

for Loop

Used to iterate over a sequence such as a list, tuple, string, dictionary, or a range of numbers.
Syntax:
Python

Copy code
for item in sequence:
    # code to execute
Example:
Python

Copy code
for i in range(5):
    print(i)  # Prints numbers 0 to 4
while Loop



Executes a block of code as long as a given condition is True.
Syntax:
Python

Copy code
while condition:
    # code to execute
Example:
Python

Copy code
count = 0
while count < 5:
    print(count)
    count += 1
    
Nested Loops


A loop inside another loop.
Commonly used for working with multi-dimensional data structures.
Example:
Python

Copy code
for i in range(3):
    for j in range(2):
        print(f"i={i}, j={j}")
        
Python provides special statements to control loop execution:

break – Exits the loop immediately.
continue – Skips the current iteration and moves to t
