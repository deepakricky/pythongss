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

While loop: A while loop is used to repeatedly execute a block of code as long as a condition remains True.
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


