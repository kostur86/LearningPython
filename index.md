# Learn Python

## Intro
This is notebook from Python learning classes

## Lesson 1 - Python types

There are 4 basic types in Python
1. Integer

Integer is a basic numeric type in Python. Example of integer are: `1`, `5`, `12980`, `-45`.
Type of integer is `int`:
```python
In [1]: type(5)
Out[1]: int
```
---

#### On iPython output
iPython is a Python interpreter with better capabilities. Easiest way to install it is to install Anaconda: https://www.anaconda.com/distribution/
When you start it (for example with `ipython` on command line) it let you insert your commands (like command line):
```python
In [1]: 
```
This mean first input, when you press enter it will disaply:
```python
Out[1]:
```
and result of command you enterd - this mean first output

---
#### On functions
Function is a block of code/functionality that can be executed with single statement. `print()`, `exit()`, or `type()` are example of functions. 
To call function in Python you have to use `<name_of_function>(<arguments>)`. Example of function is:
```
print('Hello!')
  ↑  ↑    ↑   ↑
  │  │    │   │
  └───────────────  Function name - print
     │    │   │
     └────────┴───  Parenthesis executing function - () mean this is function and
          │         we are calling it
          └───────  Arguments of a function, in this case string of characters to
                    print out on a screen

```

---
#### On type function
Function `type` return a Python type of an argument passed to a function.
To call `type` function we need to open parenthesis (meaning we are calling function) and add argument we want to get type of.
(About other types from this example you will learn later)
```python
In [1]: type(5)
Out[1]: int

In [2]: type("Hello!")
Out[2]: str

In [3]: type([1, 2, 3])
Out[3]: list
```

2. Floating point

Floating point is another basic numeric type in Python. Example of floating point numbers are: `0.5`, `12.095`, `1000000.1`, `-45.5`.
Type of floating point is `float`:
```python
In [1]: type(0.1)
Out[1]: float
```
To distinguish between integer and float you can add `.0` (or just `.`) after integer number:
```python
In [1]: type(5)
Out[1]: int

In [2]: type(5.0)
Out[2]: float

In [3]: type(5.)
Out[3]: float

In [4]: 5.0 == 5
Out[4]: True
```

---
#### On comparation operator
Single equality sign in Python is used to assign value to variable (you will learn about this later!); to compare to values you need to use double equality sign - `==`. This operation returns `True` or `False` depend if values are equal (actually it returns `bool` type, but you will learn about it in a second):
```python
In [1]: 1 == 1
Out[1]: True

In [2]: 1 == 2
Out[2]: False

In [3]: "Hello" == "Hello"
Out[3]: True

In [4]: "Hello" == "Bye!"
Out[4]: False

```

3. String of characters
