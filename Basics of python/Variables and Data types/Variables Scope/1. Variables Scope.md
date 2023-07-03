# Scope of Variables

All variables in a program may not be accessible at all locations in that program. Part(s) of the program within which the variable name is legal and accessible, is called the scope of the variable. A variable will only be visible to and accessible by the code blocks in its scope.

There are broadly two kinds of scopes in Python -
+ Global scope
+ Local scope

**Global Scope**:
A variable/name declared in the top-level segment (__main__) of a program is said to have a global scope and is usable inside the whole program (Can be accessed from anywhere in the program).
In Python, a variable declared outside a function is known as a global variable. This means that a global variable can be accessed from inside or outside of the function.

### Creating a Global Variable
Consider the given code snippet:
```python
X = "Global Variable"
def foo():
  print("value of x: п , x)
foo()
```

Here, we created a global variable x = "Global Variable". Then, we created a function foo to print the value of the global variable from inside the function. We get the output:
```
Global Variable
```
Thus we can conclude that we can access a global variable from inside any function.
***What if you want to change the value of a Global Variable from inside a function?***

Consider the given code snippet:

```python
X = 5
def foo():
  x = X+1
  print(x)
foo()
```
In this code block, we tried to update the value of the global variable x. We get an output as:
```
UnboundLocalError: local variable 'x' referenced before assignment
```
This happens because, when the command x=x-1, is interpreted, Python treats this x as a local variable and we have not defined any local variable x inside the function foo().
