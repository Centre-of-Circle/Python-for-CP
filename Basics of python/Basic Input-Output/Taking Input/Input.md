# input()
To take input from the user, we use the input() function.

input(): This function first takes the input from the user and then evaluates the expression, which means Python automatically identifies whether the user entered a string or a number or list. If the input provided is not correct then either syntax error or exception is raised by python.
Example:
```python
# Python program showing the use of input()
val = input("Enter your name: ")
print(val)
```
Output:
```
Enter your name: Cpsbd66
'Cpsbd66'
```
## How the input function works in Python :
+ When the input() function executes, program flow will be stopped until the user has given input.
+ The text or message display on the output screen to ask a user to enter input value is optional i.e. the prompt, will be printed on the screen is optional.
+ Whatever you enter as input, the input function converts it into a string. if you enter an integer value still input() function convert it into a string. You need to explicitly convert it into an integer in your code using typecasting.
Example:
```python
# Program to check input type in Python
name = input ("Enter name :")
print(name)
print ("type of name", type(name))
```
Output:
```
Enter your name: Cpsbd66
'Cpsbd66'
type of name <class 'str'>
```
Example:
```python
# Program to check input type in Python
num = int(input ("Enter number :")) print ("type of num", type (num))
print(num)
```
Output:
```
Enter number : 10
10
type of num <class 'int'>
```
## How to take space-separated input in one line in Python?
```python
x, y = input().split()
```
**Note that we don't have to explicitly specify split(' ') because split() uses any whitespace characters as a
delimiter as default.**
One thing to note in the above Python code is, both x and y would be of string. We can convert them to int using another line
Example:
```python
# Program take space-separated input in one line in Python
x, y input().split() =
print(x, y)
```
Output:
```
10 20
10 20
```
Example:
```python
# Program to check input type in Python
x, y = input().split()
a = input()
print ("type of x", type(x))
print ("type of y", type(y))
print ("type of a", type(a))
```
Output:
```
10 20
Cpsbd66
type of x <class 'str'>
type of y <class 'str'>
type of a <class 'str'>
```
