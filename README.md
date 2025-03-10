# Python-Fundamentals

## What is Python ?

It is software based language used for generating software applications. A software application works on 2 types of data. Input and Output data.
Input data is the data which we send to software application as input and output data is generated by the application as output.
e.g. A school application is software application. It works on input data which is name of student, rno, per etc and generates output which is report card.

To create software application we always need programming language. Software application runs on computer.

## Keywords:

Keywords are reserved words in Python. Their meaning is fixed and cannot be changed in program.
e.g. if,else,elif,for,while,def,class,True,False etc.

Python is case sensitive language. Nearly all keywords in Python are in lower case, except for True and False.

## Variables:
Variable is RAM memory block which is used for storing input and output values during program execution.
The variable has name and data type.
Data type specifies what type of values we can store in variable.
In python we dont need to declare variable before using it.
e.g.
a=5
a='abc def'
a=14.9
Here we have stored values of different data types in same variable 'a'.
After execution of all 3 above statements, value of a is 14.9

In python we dont need to declare variable using data type before using the variable. In python we can directly use variable name and assign it values of different data types. So Python is called dyanamically typed language.

## Data types in python:
1. primitive data types:
### A. integer:
This includes all positive and negative values without decimal point.
e.g. 5,11,-19 etc.

### B. float
This includes all positive and negative values with decimal point.
e.g. 5.5,11.1,-19.2 etc.

We can represent float values in python in 2 ways:
B.1 Normal floating format:
e.g. 5.5,11.1,-19.2

### B.2 Exponential format:
It is used for storing very large or very small values

e.g.
a=5e9
print(a)

Value stored in a is (5*(10 raised to 9))
Output:5000000000.0

e.g.
a=5e-2
print(a)

Output:0.05

Here part mentioned before e is called mantissa and after e is exponent. Mantissa can be any positive and negative number with point. Exponent can be positive and negative without point.
We can also use E instead of e.

## C. string:
It is collection of characters in single or double or triple quotes. There is no separate data type for char in python.

e.g.
a='abc def'
a="abc def"
a='m'
a="m"
d='''India is my country.
   Java is language.'''
We use triple quotes only if string value is in paragraph format.

## D. Boolean:
It has 2 values True and False.  True is represented by 1 and False by 0.
e.g.
a=True
b=True
print(a+b)
print(a-b)
print(a*b)
print(a/b)

Output:
2
0
1
1.0

### print() is predefined function in python. It will take cursor to next line after printing output.
