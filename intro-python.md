autoscale:true

# Welcome to Programming with Python!

---

## What is your current mental model of how a computer works?

---

![inline](https://www.computerscience.gcse.guru/wp-content/uploads/2018/01/computer_system.png)

---

## :information_desk_person: High Level Languages
-
## :computer: Low Level Languages

---

## Python Origins
 - General purpose programming language developed by Guido van Rossum and released in 1991.

### Stated Goals
    1. an easy and intuitive language just as powerful as those of the major competitors;
    2. open source, so anyone can contribute to its development;
    3. code that is as understandable as plain English;
    4. suitable for everyday tasks, allowing for short development times.

---

## Everything in Python is an object. Those objects have types.
- Integer
- Float
- Function
- Boolean 

## Variables are like containers that we use to store values.

---

## Opening the Python shell

---

# Let's write some python and see what happens.

```py
def greet(names):
    for name in names:
        print(f"Hi, {name}!")

our_names = ["Amy", "Rebecca", "Dawn", "Dwayne 'The Rock' Johnson"]

greet(our_names)
```

---

Try some more Python

```py
def sum(numbers):
    numbers_copy = numbers.copy()
    sum = 0
    while len(numbers_copy) > 0:
        sum += numbers[len(numbers_copy) - 1]
        numbers_copy.pop()
    print(sum)
    return(sum)

my_sum = sum([1, 2, 3, 17])
```
---

> Quick reference for Python syntax

```py
# variables
var_name = value

# functions
def my_function(parameter1, parameter2):
    # here's where the action happens
    return value_to_be_returned

# to see values in the console
print(value)

# conditionals
if a > b:
    return(a)

# loops
while b < a:
    b += 1

for item in my_list:
   # do something to the item

# remember to use snake_case instead of camelCase
``` 
---

