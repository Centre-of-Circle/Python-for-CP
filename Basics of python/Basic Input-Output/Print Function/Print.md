# Python print() Function
The print() function prints the specified message to the screen or other standard output device.

The message can be a string or any other object. The object will be converted into a string before being written to the screen.

The simplest way to produce output is using the print() function where you can pass zero or more expressions separated by commas. This function converts the expressions you pass into a string before writing to the screen.

### Syntax:
```python
print(object(s), sep-separator, end=end, file=file, flush=flush)
```

Example:

+ Printing a message on the screen:
```python
print("Hello World")
```
Output:
```
Hello World
```
+  Printing more than one object:
```python
print("Hello!","How are you?")
```
output:
```
Hello! How are you?
```
### Python end parameter in print()
By default python's print() function ends with a new line. A programmer with a C/C++ background may wonder how to print without a new line.

Python's print() function comes with a parameter called 'end'. By default, the value of this parameter is '\n', i.e. the new line character. You can end a print statement with any character/string using this parameter.

Example :
```python
print("Hello!", end = ' ')
print("How are you ?")

print("Welcome", end = " @")
print("Cpsbd66")
```
Output:
```
Hello! How are you ?
Welcome @Cpsbd66
```

Python sep parameter in print()
The separator between the arguments to print() function in Python is space by default (soft space feature), which can be modified and can be made to any character, integer, or string as per our choice. The 'sep' parameter is used to achieve the same, it is found only in python 3.x or later. It is also used for formatting the output strings.
Example:
```python
# Code for disabling the soft space feature print('Python', sep="')
# For formatting a date
print('01', '01', '2023', sep='-')
# Another example
print('tapantordas2008", 'gmail.com', sep="@")
```
output:
```
Python
01-01-2023
tapantordas2008@gmail.com
```
