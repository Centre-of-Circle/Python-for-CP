# TypeCasting
There may be times when you want to specify a type on to a variable. This can be done with type casting. Python is an OOP language, and as such, it uses classes to define data types, including its primitive types.
Type casting is the method to convert from data type to another data type, according to user's requirements. This article introduces to the different type of casting supported by Python and how to implement them.
Python supports two types of typecasting -
+ Implicit Type Conversion
+ Explicit Type Conversion

## Implicit Type Conversion
In this, method, Python automatically converts one data type into another data type. There is no user intervention.
``` python
val = 5
print(type(val))
```
output:
```
#Python automatically converts val to int.
<class 'int' >
```

Example:
```python
a = 8.0
b = 4.0
m = a * b
print(m)
print(type(m))
```
output:
```
32.0
<class 'float'>
```
