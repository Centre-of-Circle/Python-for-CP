# Introduction to data types
Data types are the classification or categorization of data items. Data types represent a
kind of value that determines what operations can be performed on that data. Numeric,
non-numeric, and Boolean (true/false) data are the most used data types. However,
each programming language has its classification largely reflecting its programming
philosophy. Python offers the following built-in data types:
+ Numbers
  * Integers
  * Floating Point Numbers
  * Complex Numbers
+ Strings
+ Boolean Values
+ List, Tuple, and Dictionary

| Type Code  | Description | Default size(in bytes) |
| ------------- | ------------- |------------- |
| int  |Integers  |4 |
| float  |Floating Point Numbers |4  |
| bool  |Boolean Values  |1  |

**Note**:- If a variable has been assigned a value of some data type. It can be reassigned as
a value belonging to some other Data Type in the future

```python
a= "Raw" # String Data Type
a= 10 # Integer Data Type
a= 5.6 # Floating Point Number Data Type
a= 1+8j # Complex Number
a= True # Boolean Value
```

# Introduction to Python Numbers
Number data types store numerical values. Python supports Integers, floating-point numbers, and complex numbers. They are defined as `int`,`float`, and `complex` classes. 
+ Integers can be of any length (Only limited by the memory available). They do have a decimal point and can be positive or negative.
+ A floating-point number is a number having a fractional part. The presence of a decimal point indicates a floating-point number. They have a precision of up to 15 digits.
+ 1 is an integer, 1.0 is a floating-point number.
+ Complex numbers are of the form, $x + yj$, where x is the real part and y is the imaginary part. We can use the type() function to know which class a variable or a value belongs to. Similarly, the instance() function is used to check if an object belongs to a particular class.

**Example**
```python
a = 5
print(a, "is of type", type(b))
b = 2.0
print(b, "is of type", type(b))
c = 1+2j
print(c, "is complex number?", isinstance(c,complex))
```

*Output*:
```
5 is of type <class ‘int’>
2.0 is of type <class ‘float’>
1+2j is a complex number? True
```
