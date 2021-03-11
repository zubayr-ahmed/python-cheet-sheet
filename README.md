# Getting started with Python. 

This is basic documentation for getting started with python. 

## Basic Types

```python
print('Hello world')
```

### Ask for input 

```python
# The input funciton allows you to prompt the user for a value
# You need to declare a variable to hold the value entered by the user
name = input('What is your name? ')
print("Welcome to Python {}!".format(name))
```

### `int`, `float`, `str`, `bytes`

```python
# int i
# float f 
# bool b
# bytes by

i = 1
f = 2.2222
b = True
by = b"fe"

print("Int {}, Float {}, bool {}, bytes {}".format(str(i), str(f), str(b), str(by)))
```

## Data structure / Containers

### `list`

```python
fruits = ['orange', 'apple', 'pear', 'banana', 'kiwi', 'apple', 'banana']
```  

#### Operations on `list`

- **`list.append(x)`**
```python
# list.append(x) # Add an item to the end of the list. 
fruits = ['orange', 'apple', 'pear', 'banana', 'kiwi', 'apple', 'banana']
fruits.append('pineapple')
print(fruits)

# list.append(x) # Equivalent to a[len(a):] = [x].
fruits[len(fruits):] = ['pen-pineapple-apple-pen']
print(fruits)
```

  - tuple
  - set
  - dict


## Conversions

  - `int("15")`  15
  - `int("3f",16)`  63 can specify integer number base in 2nd parameter
  - `int(15.56)`  15 truncate decimal part
  - `float("-11.24e8")`  -1124000000.0
  - `round(15.56,1)`  15.6 rounding to 1 decimal (0 decimal  integer number)
  - `bool(x)` False for null x, empty container x , None or False x ; True for other x
  - `str(x)` "…" representation string of x for display (cf. formatting on the back)
  - `chr(64)` '@' `ord('@')` 64 code char
  - `repr(x)` "…" literal representation string of x
  - `bytes([72,9,64])`  b'H\t@'
  - `list("abc")`  ['a','b','c']
  - `dict([(3,"three"),(1,"one")])`  {1:'one',3:'three'}
  - `set(["one","two"])`  {'one','two'}
  - separator str and sequence of str  assembled str
    - `':'.join(['toto','12','pswd'])` ==> `'toto:12:pswd'`
  - `str` splitted on whitespaces  `list` of `str`
  - `"words with spaces".split()`  ['words','with','spaces']
  - str splitted on separator str  list of str 
      - `"1,4,8,2".split(",")`  ['1','4','8','2']
  - sequence of one type  list of another type (via list comprehension)
      - `[int(x) for x in ('1','29','-3')]`  [1,29,-3]

## Variables assignments

  - x=1.2+8+sin(y)
  - a=b=c=0
  - x,y,z =1,2,3 
  - a,b = b,a swapping vars


## Sequence container indexing

  - lst = [1,2,3,4,5]
  - len(lst)
  - lst[0], lst[-1], lst[1:3], lst[-3:-1]

## Boolean Login 

  - a and b 
  - a or b
  - True / False

## Statement Blocks

  - `:` 

```python
for item in lst:
    print item
```

## Modules / Imports

  - import os
  - import numpy as nm
  - from <modle> from 

  ```
  from os import mkdir as create_directory
  create_directory("C:\\Users\\zxa22\\Documents\\xWORK\\2_GCP\\_GCP_WORKSPACE\\iaas_bd_python_scripts\\test")
  ```


## Conditional statements

  - if logical_statement:
      print (something)

  ```python
    if True:
      print("This is true")
  ```

## Exception Errors

  - try / except
  - raise
    
## Loops
  - for
  - while
  
## Generic operations on containers

## Operations on Lists

## Operations on Sets

## Files 

## String Operations




