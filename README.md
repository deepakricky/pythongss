Why python?
Python is readable and versatile, used in web dev ai and cyb etc
its most demanded language 
its also used in banking health care and etc. 
What is programming?
Programming is the process of creating a set of detailed instructions that tell a computer how to perform a specific task or solve a problem. 
set of rules we give to write that code is prog lang
Python = readable + powerful + understandable + free
print() is a built in function used to display the text and value of the variables.
Data types: Data types are categories used to define the kind of value a variable holds, which in turn determines what operations can be performed on that data.
int float string booleans 
Integer stores whole numbers.. -5,5,0,100,999
float 100.22, float data type stores decimal point numbers
Python officially defines floating-point numbers as numeric types used for decimal values.
User enters data
        │
        ▼
Python checks value
        │
        ▼
Assigns data type
        │
        ▼
Performs allowed operations
DATA TYPES
    │
    ├── int      → whole numbers
    ├── float    → decimal numbers
    ├── str      → text
    ├── bool     → True/False
    └── None     → empty value
Operators are special symbols used to perform operations on values and variables in python.
2 + 3
2 and 3 operands
+ is defined operator
1. Arithmetic operators: +, -, *, / etc.
2. Assignment operators: =, +=, -= etc.
3. Comparison operators: ==, >, >=, <, != etc.
4. Logical operators: and, or, not.
5. Membership Operators: in, not in
6. Identity Operators: is, is not
7. Bitwise operators: & | ^ ~ << >>
Numbers
   │
   ▼
Operator Applied
   │
   ▼
Python Performs Calculation
   │
   ▼
Result Returned
comparison operators are used to know relations between two values or variables

AND
| A     | B     | Result |
| ----- | ----- | ------ |
| True  | True  | True   |
| True  | False | False  |
| False | True  | False  |
| False | False | False  |
OR
| A     | B     | Result |
| ----- | ----- | ------ |
| True  | True  | True   |
| True  | False | True   |
| False | True  | True   |
| False | False | False  |

+  → add
-  → subtract
*  → multiply
/  → decimal division
// → whole division
%  → remainder
** → power
/ = returns float
// = returns floor value
= assignment
== comparison
OPERATORS
   │
   ├── Arithmetic
   │      + - * / // % **
   │
   ├── Comparison
   │      > < >= <= == !=
   │
   └── Logical
          and or not
   
Membership operators in Python are keywords used to test whether a value or a variable exists within a sequence or a collection.
Identity operators are used to determine whether two variables point to the exact same object in memory.

Bitwise operators: Bitwise operators in Python are used to perform operations on binary numbers (bits).

conditional statements:
foundation of decision making statements in python 
allow program to make decision
They allow a program to choose different actions based on whether a condition is True or False

START
             |
       [Condition?]
         /      \
      YES        NO
       |          |
    [Do A]     [Do B]
         \      /
            END

| Type         | Purpose                             |
| ------------ | ----------------------------------- |
| Simple if    | Execute code when condition is True |
| if-else      | Choose between two actions          |
| if-elif-else | Choose among multiple actions       |
| Nested if    | Condition inside another condition  |
| Multiple if  | Independent condition checks        |

**if else syntax:**

if condition:
    statements
else:
    statements

**if elif else syntax:**

if condition1:
    code
elif condition2:
    code
elif condition3:
    code
else:
    code
Conditions Always Return Boolean Values
Operators used in cond stat are comparison operators

Loop: Loop is used to repeatedly execute a block of code efficiently without rewriting it

While loop: A while loop is used to repeatedly execute a block of code as long as a condition remains True.
Syntax:

while condition:
    statements

For: A for loop is used to iterate through a sequence like list, tuple, or string [iterables] 
In for loop we know exactly how many times the block should execute.

for i in range(stop):
    ...
for i in range(start, stop):
    ...
for i in range(start, stop, step):
    ...

repetitions are known in for and not known in while loop

**LOOP CONTROL STATEMENTS**

Sometimes we need to change loop behavior.

Python provides:

break
continue
pass

Nested Loop: A nested loop is simply a loop inside another loop.
Nested Loops: for i in range():
    for j in range():
        statements

LOOPS
│
├── FOR LOOP
│   ├── range()
│   ├── list
│   ├── string
│   └── tuple
│
├── WHILE LOOP
│   ├── condition
│   └── counter update
│
├── CONTROL STATEMENTS
│   ├── break
│   ├── continue
│   └── pass
│
└── NESTED LOOPS
    ├── tables
    └── patterns

String is a sequence of characters enclosed with in " " or ' ' or ''' ''' (for mult line text)
Strings are immutable, once created cannot be changed directly.
len() used to know lenghth of the string. space is also counted while checking len of string.

String indexing:
Python

P  y  t  h  o  n
0  1  2  3  4  5
-6 -5 -4 -3 -2 -1

Positive → Left to Right →
Negative → Right to Left ←

String slicing: extracting a part of string
Syntax:
string[start:end]

Methods are bulding tool for strings

Methods of strings:
upper()
lower()
title()
strip()
replace()
split(): Converts a string into a list.

List:list is a built-in, mutable, and ordered collection of items enclosed in square brackets [] and separated by commas. It is a foundational data structure that allows you to store, alter, and arrange multiple elements—even of different data types—under a single variable name.
Syntax: my_list = [item1, item2, item3]

# Integer list
numbers = [1, 2, 3, 4, 5]

# String list
names = ["Alice", "Bob", "Charlie"]

# Mixed data types
mixed = [1, "hello", 3.14, True]

# Empty list
empty = []

remove(): remove by value
delete(): removes my index

**List statistics**

len()
print(len(numbers))

Counts total items.

sum()
print(sum(numbers))

Adds all numbers.

min()
print(min(numbers))

Smallest value.

max()
print(max(numbers))

Largest value.

**List comprehension**
EX:
squares = [i ** 2 for i in range(1, 6)]
print(squares)

For coping the lists:
b = a.copy()
or
b = a[:]

**Tuples, Sets and Dictionaries:**
Tuple: Immutable and ordered
()
Set: A set is a collection of unique items.
{}
Union (a | b)
Intersection a & b
Difference a - b
Bitwise XOR print(a ^ b)
Dictionaries: A ⁠Python dictionary is a built-in data structure that stores information in key-value pairs, allowing you to retrieve data efficiently using a unique label rather than a numeric position. It is defined using curly braces {} with colons : separating keys and values

CREATING DICTIONARIES
student = {
    "name": "Josh",
    "age": 22,
    "grade": "A",
    "courses": ["Python", "AI"]
}
ACCESSING VALUES
print(student["name"])

Output:

Josh
USING GET()
print(student.get("age"))

Safer method.

DEFAULT VALUES
print(student.get("gpa", 0.0))

If key missing:

Return default value.

ADDING DATA
student["university"] = "PRIST"
UPDATING DATA
student["age"] = 23
REMOVING DATA
del student["grade"]

OR

removed = student.pop("age")
ITERATING THROUGH DICTIONARIES 🔄
for key, value in student.items():
    print(f"{key}: {value}")
IMPORTANT METHODS
print(student.keys())
print(student.values())
print(len(student))

**Functions**: A function is a reusable block of code that runs only when you call it.
Example:
def greet_user(name):
    print(f"Hello, {name}!")

greet_user("Josh")

Types of FunctionsBuilt-in Functions: Pre-installed utilities ready to use out-of-the-box, such as print(), len(), type(), and max().User-Defined Functions: Custom blocks of code built by developers to handle specific application logic.Anonymous (Lambda) Functions: Short, single-expression functions created using the lambda keyword instead of def.Inner / Nested Functions: Functions defined inside another function, often used to hide helper logic or create closures.

A lambda function is a small, anonymous function that is defined without a name. While normal functions in Python are created using the def keyword, lambda functions use the lambda keyword.
lambda arguments: expression
Example:
square = lambda x: x ** 2

print(square(5))  # Output: 25

**File Handling**
File handling in Python allows you to create, read, update, and delete files permanently on a storage device using the built-in open() function. Instead of manually opening and closing files, the modern industry standard is to use the with statement context manager, which handles resource cleanup automatically.

open(filename, mode)
'r': Read mode (Default). 
Ex: file = open("students.txt", "r")

with open("students.txt", "r") as file:
    content = file.read()

| Mode   | Meaning      |
| ------ | ------------ |
| `"r"`  | Read         |
| `"w"`  | Write        |
| `"a"`  | Append       |
| `"r+"` | Read + Write |
| `"rb"` | Read Binary  |
| `"wb"` | Write Binary |

Reading a file:
Method 1 - reading entire file
with open("students.txt", "r") as file:
    content = file.read()
print(content)

method 2 - reading line by line
with open("students.txt", "r") as file:
    for line in file:
        print(line.strip())

**Append**: Append mode ('a') adds new content directly to the end of an existing file without modifying or deleting any of its current data.
Example:
with open("students.txt", "a") as file:
    file.write("Vamshi: 79\n")

**Reading into a list**
with open("students.txt", "r") as file:
    lines = file.readlines()

**Exception handling** in ⁠Python is a mechanism used to manage runtime errors and prevent applications from crashing abruptly.
Syntax

try:
    # risky code

except:
    # handles error




















