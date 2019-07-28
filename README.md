# pythonnotes
IT3 section
https://chat.whatsapp.com/Dy9HubaOWCE7Bu8bvkUxo8

Github Repo link:-
================

https://github.com/bhanuwithpython2019-IT3/pythonnotes.git



installation:-
==============
After installation,

Goto start menu, see python folder in list and
open python cmd prompt.

To verify python is installed or not:-
-------------------------------------
$ python --version

python path:-
-------------
C:\Users\user\AppData\Local\Programs\Python\Python37-32\Scripts

open command prompt:-
=====================
$ python
>>> print("Hello world")
 Hello world

>>>"Hello world"
 'Hello world'

Reserved or keywords:-
-----------------------
35 keywords;
>>> import keyword
>>>keyword.kwlist
['False', 'None', 'True', 'and', 'as', 'assert', 'async', 'await', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']

Keywords:-
==========
'False', 
'None', 
'True', 
'and', 
'as', 
'assert',
 'async',
 'await',
 'break', 
'class', 
'continue', 
'def', 
'del', 
'elif', 
'else', 
'except', 
'finally', 
'for', 
'from', 
'global',
 'if',
 'import',
 'in',
 'is', 
'lambda',
 'nonlocal',
 'not', 
'or', 
'pass', 
'raise', 
'return', 
'try', 
'while', 
'with', 
'yield'

To exit:-
========
exit()-- to exit the command prompt

Python is an interpreted programming language, this means that as a developer you write Python (.py) files in a text editor and then put those files into the python interpreter to be executed.

writing in a file:-
-------------------
vi firstfile.py

#!/usr/bin/python
print("hello world")


execution of the python program:-
================================

$ python filename

$ python firstfile.py

firstfile.py is the name of the python file.

Python indentations:-
====================
in Python the indentation is very important.

Python uses indentation to indicate a block of code.

if 5 > 2:
  print("Five is greater than two!")# block of code

Python will give you an error if you skip the indentation:
if 5 > 2:
print("Five is greater than two!")

You will get IdentationError


python comments:-
==================

* Python has commenting capability for the purpose of in-code documentation.

* Comments start with a #, and Python will render the rest of the line as a comment:

Comments can be used to explain Python code.
Comments can be used to make the code more readable.
Comments can be used to prevent execution when testing code.

#This is a comment.
print("Hello, World!")

Comments can be placed at the end of a line, and Python will ignore the rest of the line:
print("Hello, World!") #This is a comment

it can also be used to prevent Python from executing code:

#print("Hello, World!")
print("Hello, Python!")

multi line comments:-
====================
no multiline comment.

Use you can use a multiline string.(triple quotes).

"""
group of lines.
This is a comment
written in 
more than just one line
"""
print("Hello, World!")

onemore way

'''
group of lines.
This is a comment
written in 
more than just one line
'''
print("Hello, World!")


Python variables:-
------------------
Variables in Python:



=> Python has no command for declaring a variable.

* Variables are containers for storing data values.

* A variable is created the moment you first assign a value to it.
  
  x = 5
  y = "Hello, World!"

Variables do not need to be declared with any particular type and can even change type after they have been set.

x = 4 # x is of type int
x = "python" # x is now of type str
print(x)

String variables can be declared either by using single or double quotes

x = "python"
# is the same as
x = 'python'


variables conventions:-
=====================

A variable can have a short name (like x and y) or a more descriptive name (age, carname, total_volume, _age).


A variable name must start with a letter or the underscore character
A variable name cannot start with a number
A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
Variable names are case-sensitive (age, Age and AGE are three different variables).

Assign Value to Multiple Variables:-

Python allows you to assign values to multiple variables in one line:
x, y, z = "Hyd", "Blr", "Che"
print(x)
print(y)
print(z)

And you can assign the same value to multiple variables in one line:

x = y = z = "Hyderabad"
print(x)
print(y)
print(z)

Output to screen:-
=================
The Python print statement is often used to output variables.

print()

x = "Easy to learn"
print("Python is " + x)

You can also use the + character to add a variable to another variable:

x = "Python is "
y= "easy to learn"
z= x+y
print(z)

x=5
y=15
print(x+y)

If you try to combine a string and a number, 
Python will give you an error:

x = 5
y = "John"
print(x + y) # TypeError

The print function can accept 4 different parameters:
 i.e. sep, end, file, and flush. 

To look at the description of the function, you can type: 
help(print)

file: a file-like object (stream); defaults to the current sys.stdout.
sep: string inserted between values, default a space.
end: string appended after the last value, default a newline.
flush: whether to forcibly flush the stream.

print("Hello", "world",sep='\n')

end():-
=======
a=10
b=20
c=30
print(a,b,c)
print("hello")
print(a,end=" ")
# by default end value is new line
print(b,end=" ")
print(c,end=" ")

Datatypes:-
----------

Data Type represents the type of data present inside a variable.
         
In Python we are not required to specify the type explicitly.

 Based on value provided, the type will be assigned automatically. Hence Python is Dynamically Typed Language.

Python contains several inbuilt functions
1.type()
to check the type of variable
2. id()
to get address of object
3. print()
to print the value
                                        
 In Python everything is object

Basic datatypes:
================
1. int
2. float
3. complex
4.boolean
5. string

Complex or collection data types:
=================================
List
Set
Tuple
Dictionary

1. int/float/complex - numeric type:-
   ==================================
   x = 1    # int
   y = 2.8  # float
   z = 1j   # complex

type():- 
To verify the type of any object in Python, use the type() function

print(type(x))
print(type(y))
print(type(z))

Int
Int, or integer, is a whole number, positive or negative, without decimals, of unlimited length.

x = 1
y = 35656222554887711
z = -3255522

print(type(x))
print(type(y))
print(type(z))

Float
Float, or "floating point number" is a number, positive or negative, containing one or more decimals.

x = 1.10
y = 1.0
z = -35.59

print(type(x))
print(type(y))
print(type(z))

Float can also be scientific numbers with an "e" to indicate the power of 10.

x = 35e3
y = 12E4
z = -87.7e100

print(type(x))
print(type(y))
print(type(z))

Complex
Complex numbers are written with a "j" as the imaginary part:
not i .

x = 3+5j
y = 5j
z = -5j

print(type(x))
print(type(y))
print(type(z))

Type Conversions:-
===================
You can convert from one type to another with the int(), float(), and complex() methods:

x = 1 # int
y = 2.8 # float
z = 1j # complex

#convert from int to float:
a = float(x)
print(a)

#convert from float to int:
b = int(y)

#convert from int to complex:
c = complex(x)

print(a)
print(b)
print(c)

print(type(a))
print(type(b))
print(type(c))

Note: You cannot convert complex numbers into another number type.

id()

Random Number
Python does not have a random() function to make a random number, but Python has a built-in module called random that can be used to make random numbers:

Import the random module, and display a random number between 1 and 9:

import random
print(random.randrange(1,10))

input():-
=========
a=input("Enter first no:)
b=input("Enter second no:)
print(a+b)



Typecasting:-
-------------
when you want to specify a type on to a variable. This can be done with casting. 

Casting in python is therefore done using constructor functions:

int() - constructs an integer number from an integer literal, a float literal (by rounding down to the previous whole number), or a string literal (providing the string represents a whole number)

float() - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)

str() - constructs a string from a wide variety of data types, including strings, integer literals and float literals.



x = int(1)   # x will be 1
y = int(2.8) # y will be 2
z = int("3")

x = float(1)
y = float(2.8)
z = float("3")
w = float("4.2")
print(x)
print(y)
print(z)
print(w)

Strings:

x = str("s1") # x will be 's1'
y = str(2)    # y will be '2'
z = str(3.0)  # z will be '3.0'

a=int(input("Enter first no:))
b=int(input("Enter second no:))
print(a+b)


a=string(input("Enter first Name))
b=string(input("Enter Last Name:))
print(a+b)

Python Strings:-
=================

String literals in python are surrounded by either single quotation marks, or double quotation marks.

'hello' is the same as "hello".

You can display a string literal with the print() function:
print("Hello")
print('Hello')

Assign String to a Variable:-
Assigning a string to a variable is done with the variable name followed by an equal sign and the string:

a = "Hello"
print(a)

Multiline Strings
You can assign a multiline string to a variable by using three quotes:

a = """Python is simple,
easy to learn,
easy to work
easy to maintain."""
print(a)

Or three single quotes:

a = '''Python is simple,
easy to learn,
easy to work
easy to maintain.'''
print(a)

Strings are Arrays in python:-
=============================
Python does not have a character data type, a single character is simply a string with a length of 1. 

Square brackets can be used to access elements of the string.

Get the character at position 1 (remember that the first character has the position 0):

a = "Hello, World!"
print(a[1])
o/p- e

Substring. 

Get the characters from position 2 to position 5 (not included):

b = "Hello, World!"
print(b[2:5])
o/p- llo

string methods:-
================
The len() method returns the length of a string:
a = "Hello, World!"
print(len(a))

The strip() method removes any whitespace from the beginning or the end:
a = " Hello, World! "
print(a.strip()) # returns "Hello, World!"

The lower() method returns the string in lower case:
a = "Hello, World!"
print(a.lower())

The upper() method returns the string in upper case:
a = "Hello, World!"
print(a.upper())

The replace() method replaces a string with another string:

a = "Hello, World!"
print(a.replace("H", "J"))

The split() method splits the string into substrings if it finds instances of the separator:

a = "Hello, World!"
print(a.split(",")) # returns ['Hello', ' World!']

we cannot combine strings and numbers like this:


age = 35
txt = "My name is John, I am " + age
print(txt)

But we can combine strings and numbers by using the format() method!

The format() method takes the passed arguments, formats them, and places them in the string where the placeholders {} are:

Example
Use the format() method to insert numbers into strings:

age = 35
txt = "My name is Bhanu, and I am {}"
print(txt.format(age))

The format() method takes unlimited number of arguments, and are placed into the respective placeholders:

quantity = 3
itemno = 786
price = 50.00
myorder = "I want {} pieces of item {} for {} dollars."
print(myorder.format(quantity, itemno, price))

You can use index numbers {0} to be sure the arguments are placed in the correct placeholders:

quantity = 3
itemno = 786
price = 50.00
myorder = "I want to pay {2} dollars for {0} pieces of item {1}."
print(myorder.format(quantity, itemno, price)) 

String slicings:-
================
slice means a piece.
[ ] operator is called slice operator,which can be used to retrieve parts of String.

In Python Strings follows zero based index.
The index can be either +ve or -ve.
+ve index means forward direction from Left to   Right -ve index means backward direction from Right to Left

-5 -4 -3 -2 -1
 b  h  a  n  u
 1  2  3  4  5

Syntax: s[bEginindex:endindex:step]

bEginindex:From where we have to consider slice(substring) endindex: We have to terminate the slice(substring) at endindex-1 step: incremented value

Note: If we are not specifying bEgin index then it will consider from bEginning of the string.
If we are not specifying end index then it will consider up to end of the string
The default value for step is 1


s= "bhanu"

s[0]

s[1]

s[-1]

s[20]

IndexError: string index out of range

s[1:10]

s[1:]

s[:4]

s[:]

s[-4:-1]
s[::-1]

s="Learning Python is very very easy!!!"

s[1:7:1]
'earnin'

s[1:7]
'earnin'

s[1:7:2]
'eri'

s[:7]
'Learnin'

s[7:]
'g Python is very very easy!!!'

s[::]
'Learning Python is very very easy!!!'

s[:]
'Learning Python is very very easy!!!'

s[::-1]
'!!!ysae yrev yrev si nohtyP gninraeL'

***Note:
In the backward direction if end value is -1 then result is always empty.

In the forward direction if end value is 0 then result is always empty.

In forward direction:

default value for bEgin: 0
default value for end: length of string
default value for step: +1

In backward direction:

default value for bEgin: -1
default value for end: -(length of string+1)
Note: Either forward or backward direction, we can take both +ve and -ve values for bEgin and end index.

Mathematical Operators for String:

We can apply the following mathematical operators for Strings.

	+ operator for concatenation
	* operator for repetition
print("tecno"+"soft") 
print("tecno"*2) 

	To use + operator for Strings, compulsory both arguments should be str type

	To use * operator for Strings, compulsory one argument should be str and other argument should be int








s*3



len() in-built function:

We can use len() function to find the number of characters present in the string.
len(s)

Control Flow :-
============
What are if...else statement in Python?
Decision making is required when we want to execute a code only if a certain condition is satisfied.
The if…elif…else statement is used in Python for decision making.
Python if Statement Syntax
If  test expression:
    statement(s)
Here, the program evaluates the test expression and will execute statement(s) only if the text expression is True.
If the text expression is False, the statement(s) is not executed.
In Python, the body of the if statement is indicated by the indentation. 
Body starts with an indentation and the first unindented line marks the end.
Python interprets non-zero values as True. None and 0 are interpreted as False.
Example: Python if Statement
# If the number is positive, we print an appropriate message
num = 3
if num > 0:
    print(num, "is a positive number.")
print("This is always printed.")
num = -1
if num > 0:
    print(num, "is a positive number.")
print("This is also always printed.")
When you run the program, the output will be:
3 is a positive number
This is always printed
This is also always printed.
In the above example, num > 0 is the test expression.
The body of if is executed only if this evaluates to True.
When variable num is equal to 3, test expression is true and body inside body of if is executed.
If variable num is equal to -1, test expression is false and body inside body of if is skipped.
The print() statement falls outside of the if block (unindented). Hence, it is executed regardless of the test expression.





Python if...else Statement
Syntax of if...else
if test expression:
    Body of if
else:
    Body of else
The if..else statement evaluates test expression and will execute body of if only when test condition is True.
If the condition is False, body of else is executed. Indentation is used to separate the blocks.
Example of if...else
# Program checks if the number is positive or negative
# And displays an appropriate message
num = 3
# Try these two variations as well. 
# num = -5
# num = 0
if num >= 0:
    print("Positive or Zero")
else:
    print("Negative number")

In the above example, when num is equal to 3, the test expression is true and body of if is executed and body of else is skipped.
If num is equal to -5, the test expression is false and body of else is executed and body of if is skipped.
If num is equal to 0, the test expression is true and body of if is executed and body of else is skipped.
Python if...elif...else Statement
Syntax of if...elif...else
if test expression:
    Body of if
elif test expression:
    Body of elif
else: 
    Body of else
The elif is short for else if. It allows us to check for multiple expressions.
If the condition for if is False, it checks the condition of the next elif block and so on.
If all the conditions are False, body of else is executed.
Only one block among the several if...elif...else blocks is executed according to the condition.
The if block can have only one else block. But it can have multiple elif blocks.
Example of  if...elif...else
# In this program, 
# we check if the number is positive or
# negative or zero and 
# display an appropriate message
num = 3.4
# Try these two variations as well:
# num = 0
# num = -4.5
if num > 0:
    print("Positive number")
elif num == 0:
    print("Zero")
else:
    print("Negative number")
When variable num is positive, Positive number is printed.
If num is equal to 0, Zero is printed.
If num is negative, Negative number is printed
________________________________________
Python Nested if statements
We can have a if...elif...else statement inside another if...elif...else statement. This is called nesting in computer programming.
Any number of these statements can be nested inside one another. Indentation is the only way to figure out the level of nesting. This can get confusing, so must be avoided if we can.
Python Nested if Example
# In this program, we input a number
# check if the number is positive or
# negative or zero and display
# an appropriate message
# This time we use nested if

num = float(input("Enter a number: "))
if num >= 0:
    if num == 0:
        print("Zero")
    else:
        print("Positive number")
else:
    print("Negative number")



Output 1
Enter a number: 5
Positive number
Output 2
Enter a number: -1
Negative number
Output 3
Enter a number: 0
Zero
What is for loop in Python?
The for loop in Python is used to iterate over a sequence (list, tuple, string) or other iterable objects. Iterating over a sequence is called traversal.
Syntax of for Loop
for val in sequence:
	Body of for
Here, val is the variable that takes the value of the item inside the sequence on each iteration.
Loop continues until we reach the last item in the sequence. The body of for loop is separated from the rest of the code using indentation.

Example: Python for Loop
# Program to find the sum of all numbers stored in a list
# List of numbers
numbers = [6, 5, 3, 8, 4, 2, 5, 4, 11]
# variable to store the sum
sum = 0
# iterate over the list
for val in numbers:
    sum = sum+val
# Output: The sum is 48
print("The sum is", sum)
when you run the program, the output will be:
The sum is 48

The range() function
We can generate a sequence of numbers using range() function. range(10) will generate numbers from 0 to 9 (10 numbers).
We can also define the start, stop and step size as range(start,stop,step size). step size defaults to 1 if not provided.
This function does not store all the values in memory, it would be inefficient. So it remembers the start, stop, step size and generates the next number on the go.
To force this function to output all the items, we can use the function list().
The following example will clarify this.
# Output: range(0, 10)
print(range(10))

# Output: [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
print(list(range(10)))

# Output: [2, 3, 4, 5, 6, 7]
print(list(range(2, 8)))

# Output: [2, 5, 8, 11, 14, 17]
print(list(range(2, 20, 3)))	
We can use the range() function in for loops to iterate through a sequence of numbers. It can be combined with the len() function to iterate though a sequence using indexing. Here is an example.
# Program to iterate through a list using indexing

movie= ['Aravinda sametha', 'Brand Babu', 'Hello guru premakosamey']
# iterate over the list using index
for i in range(len(movie)):
    print("I like", movie[i])
When you run the program, the output will be:
I like Aravinda Sametha
I like Brand Babu
I like Hello guru premakosamey
for loop with else
A for loop can have an optional else block as well. The else part is executed if the items in the sequence used in for loop exhausts.
break statement can be used to stop a for loop. In such case, the else part is ignored.
Hence, a for loop's else part runs if no break occurs.
Here is an example to illustrate this.
digits = [0, 1, 5]
for i in digits:
    print(i)
else:
    print("No items left.")
When you run the program, the output will be:
0
1
5
No items left.
Here, the for loop prints items of the list until the loop exhausts. When the for loop exhausts, it executes the block of code in the else and prints
No items left.

What is while loop in Python?
The while loop in Python is used to iterate over a block of code as long as the test expression (condition) is true.
We generally use this loop when we don't know beforehand, the number of times to iterate.
Syntax of while Loop in Python
while test_expression:
    Body of while
In while loop, test expression is checked first. The body of the loop is entered only if the test_expression evaluates to True. After one iteration, the test expression is checked again. This process continues until the test_expression evaluates to False.
In Python, the body of the while loop is determined through indentation.
Body starts with indentation and the first unindented line marks the end.
Python interprets any non-zero value as True. None and 0 are interpreted as False.
Example: Python while Loop
# Program to add natural
# numbers upto 
# sum = 1+2+3+...+n
# To take input from the user,
# n = int(input("Enter n: "))
n = 10
# initialize sum and counter
sum = 0
i = 1
while i <= n:
    sum = sum + i
    i = i+1    # update counter
# print the sum
print("The sum is", sum)

When you run the program, the output will be:
Enter n: 10
The sum is 55
In the above program, the test expression will be True as long as our counter variable i is less than or equal to n (10 in our program).
We need to increase the value of counter variable in the body of the loop. This is very important (and mostly forgotten). Failing to do so will result in an infinite loop (never ending loop).
Finally the result is displayed.
________________________________________
while loop with else
Same as that of for loop, we can have an optional else block with while loop as well.
The else part is executed if the condition in the while loop evaluates to False.
The while loop can be terminated with a break statement. In such case, the else part is ignored. Hence, a while loop's else part runs if no break occurs and the condition is false.
Here is an example to illustrate this.
# Example to illustrate
# the use of else statement
# with the while loop
counter = 0
while counter < 3:
    print("Inside loop")
    counter = counter + 1
else:
    print("Inside else")
Output
Inside loop
Inside loop
Inside loop
Inside else
Here, we use a counter variable to print the string Inside loop three times.
On the forth iteration, the condition in while becomes False. Hence, the else part is executed.

What is the use of break and continue in Python?
In Python, break and continue statements can alter the flow of a normal loop.
Loops iterate over a block of code until test expression is false, but sometimes we wish to terminate the current iteration or even the whole loop without checking test expression.
The break and continue statements are used in these cases.
Python break statement
The break statement terminates the loop containing it. Control of the program flows to the statement immediately after the body of the loop.
If break statement is inside a nested loop (loop inside another loop), break will terminate the innermost loop.
Syntax of break
break


Example: Python break
# Use of break statement inside loop
for val in "string":
    if val == "i":
        break
    print(val)
print("The end")

Output
s
t
r
The end
In this program, we iterate through the "string" sequence. We check if the letter is "i", upon which we break from the loop. Hence, we see in our output that all the letters up till "i" gets printed. After that, the loop terminates.
________________________________________
Python continue statement
The continue statement is used to skip the rest of the code inside a loop for the current iteration only. Loop does not terminate but continues on with the next iteration.
Syntax of Continue
continue
Example: Python continue
# Program to show the use of continue statement inside loops
for val in "string":
    if val == "i":
        continue
    print(val)
print("The end")

Output
s
t
r
n
g
The end
This program is same as the above example except the break statement has been replaced with continue.
We continue with the loop, if the string is "i", not executing the rest of the block. Hence, we see in our output that all the letters except "i" gets printed.



