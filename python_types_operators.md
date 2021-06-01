# Python Types, Operators, and Collections

---

# **Built-in Data Types in Python**
_Everything in Python is an object, and every object has a type. The type tells us what we can do with that object. Let's look at the most commonly used data types that come built in to Python._

---

**String** - collection of characters, including letters, spaces, and special characters
**Integer** - same as what they are in math, positive and negative whole numbers and 0
**Float** - like a decimal, but not as precise (don't use these for money)
**Boolean** - has a value of True or False, like a switch that can either be on or off

---

# Operators

The operators ```+, -, *, /``` are used the way we are familiar with using them. _Exercise: try using these operators on integers, floats, and strings and observe the results._

---

>But what if we want to have a collection of multiple objects?

---

# Python has a number of ways to represent collections of objects. We will focus on three of them:

- lists
- tuples
- dictionaries

---

# Lists

-enclosed by square brackets []
-items separated by a comma, you can include a trailing comma
	```colors = ["red", "green", "blue",]```
-position of an item in a list is called `index` and starts at 0

---

# Some built-in list methods
-> **append** adds an item to the end of the list ```colors.append("yellow")```

-> **pop** returns and removes the last item in the list, or the item in the index position if you pass one in the () ```last = colors.pop(), last = "yellow"```

_Exercise: try out some of the other built-in list methods described in the Python docs https://docs.python.org/3/tutorial/datastructures.html_ 

--- 

# Tuples
-act like lists, but they are *immutable* (cannot be changed)
-arguments in functions that take multiple arguments are structured as tuples
-enclosed in ()
-tuples can be _unpacked_, with each item getting assigned to a variable in a new tuple

---

> Exercise: run this line of code and then inspect the value of each variable.

```py
(a, b, c) = (1, 2, 3)
```

--- 

# Dictionaries

Unordered collections in python that allow us to represent relationships between keys and values.

```py
my_dict = { 
	"key1": "value1",
	"key2": "value2",
	"key3": "value3",
	}
```

---

# Using dictionaries

Retrieve values by using the key and [] notation:

```py 
my_dict = { 
	"key1": "value1",
	"key2": "value2",
	"key3": "value3",
	}
my_dict['key2'] = 'value2'

# OR use get, which doesn't break if the key happens not to be present

my_dict.get('key4') = None
```
---

Add or update value by assigning the value to its corresponding key

```py
my_dict['key4'] = 'value4'
my_dict['key2'] = 'new_value2'
```

_Remember: unlike lists and tuples, dictionaries are not ordered and do not have indexes_

---







	
 
