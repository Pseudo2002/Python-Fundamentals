### Accepting Input From Users 

## 1. Accepting string input from user:


e.g.
a=input("Enter message:")

print("The message is",a)

Output:
Enter message:india is my country
The message is india is my country



e.g.
a=input("Enter 1st number:")
b=input("Enter 2nd number:")
c=a+b
print("The addition is",c)

Output:
Enter 1st number:5
Enter 2nd number:10
The addition is 510

input() is predefined function in python. It displays message we have passed to it. It will then accept input from user and return it as string.


Enter 1st number:5.8
Enter 2nd number:8.9
The addition is 5.88.9



## 2. Accepting integer input:
a=int(input("Enter number:"))
print("The value of a is",)

Output:
Enter number:5
The value of a is 5

int() is predefined function in Python.
int() function accepts string input and converts to integer format.
If we pass float value or value with decimal point to int function it gives runtime error.



## 3. Accepting float input:
a=float(input("Enter number:"))
print("The value of a is",)

Output:
Enter number:5
The value of a is 5.0


float() is predefined function in Python.
float() function accepts string input and converts to flat format.
If we pass integer value or value without decimal point to float function it doesn't give error but returns value with decimal point.


4. Accepting integer,float, Boolean:
a=eval(input("Enter 1st number:"))
b=eval(input("Enter 2nd number:"))
c=a+b
print("The addition is",c)


Output:
Enter 1st number:5
Enter 2nd number:10
The addition is 15



Output:
Enter 1st number:5.4
Enter 2nd number:10
The addition is 15.4


Output:
Enter 1st number:True
Enter 2nd number:True
The addition is 2



Floor division:
It is represented by //
a//b returns floor value after diving a by b. Floor value of decimal point value is that integer value which is close to float value and smaller than it.
e.g. Floor value of 4.9 is 4, of 4.1 is 4
Floor value of -4.9 is-5

a=7
b=4
c=a//b
a/b is 1.75, floor value of 1.75 is 1
c is 1


a=-7
b=4
c=a//b
c is -2


a=-7
b=-4
c=a//b
c is 1


a=7
b=-4
c=a//b
c is -2







How remainder is calculated in python:
e.g.1
a=7
b=4
c=a%b
Internally compiler calculates value of a//b
a//b is 1
Here a//b which is 1  is considered as quotient
a is dividend, b is divisor

Now euclids theorem is applied
dividend=(q*d)+r

7=(1*4)+r
r=7-4=3
r=3




e.g.2
a=-7
b=4
c=a%b
Internally compiler calculates value of a//b
a//b is -2
Here a//b which is -2  is considered as quotient
a is dividend, b is divisor

Now euclids theorem is applied
dividend=(q*d)+r

-7=(-2*4)+r
r=-7+8=1
r=1



e.g.3
a=-7
b=-4
c=a%b
Internally compiler calculates value of a//b
a//b is 1
Here a//b which is 1  is considered as quotient
a is dividend, b is divisor

Now euclids theorem is applied
dividend=(q*d)+r

-7=(1*-4)+r
r=-7+4=-3
r=-3
