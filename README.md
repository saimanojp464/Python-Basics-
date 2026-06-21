Python Basics Documentation
Objective

This program demonstrates the fundamentals of Python programming, including:

Variable declaration and assignment

Multiple variable assignment

Basic data types

Using the type() function

Type conversion between integers and floating-point numbers

Program Description

1. Variable Initialization
   
a = 2

print(a)

*)A variable a is assigned the value 2.

*)The value of a is printed.

2. Variable Reassignment

a = 10

print(a)

The existing variable a is updated with a new value 10.

Python allows variables to be reassigned at any time.

3. Assigning the Same Value to Multiple Variables

a = b = 1

print(a)

Both a and b are assigned the value 1 in a single statement.

The value of a is displayed.

4. Multiple Variable Assignment

a, b, c = 1, 2, 3

print(b)

print(a)

print(c)

print(a, b, c)

Three variables are assigned different values simultaneously.

Individual variables and all variables together are printed.

5. Integer Data Type

a = 1

b = -1

print(type(a), type(b))

Demonstrates positive and negative integers.

type() confirms that both variables are of type int.

6. Boolean Data Type

a = True

b = False

print(type(a), type(b))

Demonstrates Boolean values.

type() returns bool for both variables.

7. Float Data Type

a = 2.0

print(type(float))

The variable a contains a floating-point value.

However, type(float) returns <class 'type'> because float is a built-in class.

To check the type of the variable, use print(type(a)), which returns <class 'float'>.

8. Complex Data Type

v = 1 + 2j

print(type(v))

Demonstrates a complex number.

type() returns complex.

9. Integer to Float Conversion

a = 2

print(float(a))

Converts the integer 2 into the floating-point value 2.0.

10. Integer Conversion

a = 1

print(int(a))

Converts the value to an integer using the int() function.




Conclusion

This program introduces essential Python concepts such as variables, different built-in data types, checking data types with type(), assigning values in multiple ways, and converting values using int() and float(). These concepts form the foundation for writing more advanced Python programs.

















