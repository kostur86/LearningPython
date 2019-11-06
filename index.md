# Learn Python

## Intro
This is notebook from Python learning classes

## Lesson 1 - Python types

There are 4 basic types in Python
1. Integer

Integer is a basic numeric type in Python. Example of integer are: `1`, `5`, `12980`, `-45`.
Type of integer is `int`:
```
In [1]: type(5)
Out[1]: int
```


---
#### On functions
To call function in Python you have to use `<name_of_function>(<arguments>)`. Example of function is:
```
print('Hello!')
  ^  ^    ^   ^
  |  |    |   |
  +---------------  Function name - print
     +--------+---  Parenthesis executing function - () mean this is function and
          |         we are calling it
          +-------  Arguments of a function, in this case string of characters to
                    print out on a screen
```

---
#### On type function
Function `type` return a Python type of an argument passed to a function.
To call `type` function we need to open parenthesis (meaning we are calling function) and add argument we want to get type of.
```
type(1)
```
