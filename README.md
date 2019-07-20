# pythonnotes
IT3 section
https://chat.whatsapp.com/Dy9HubaOWCE7Bu8bvkUxo8


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

