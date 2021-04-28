
Object Oriented Programming
April 27, 2021

---
Object Oriented Programming uses *classes* to represent real-world entities. *Classes* are like blueprints containing the general structure of the entity, while _instances_ are individual embodiments of a *class*. For example, "Pet" could be a class while "Nutmeg" is an instance of that class with the attributes "fuzzy", "stubborn," and "chonky."



---
^ Abstraction could also be described as modeling or generalization, highlighting relevant information to the exclusion of less relevant information
^ Encapsulation means that external code is unconcerned with internal workings of a class
^ Inheritance is creating new classes based on the characteristics of existing classes
^ Polymorphism refers to the capacity for an object to be a member and possess the attributes of multiple classes

### Principles of Object Oriented Programming
- Abstraction
- Encapsulation
- Inheritance
- Polymorphism

---

### Classes in Python
 
```py 
class Pet:
    def __init__(self, name, species, personality, size, texture):
        self.name = name
        self.species = species
	self.personality = personality
	self.size = size
	self.texture = texture
    
    def __str__(self):
        return f'{self.name} the {self.species}'
```
---

The `__init__()` method is built in to Python classes and, when called, creates a new *instance* of that *class*. Writing the name of the class with () and the necessary arguments causes `__init__()` to be called.

---

```
nutmeg = Pet("Nutmeg", "dog", "stubborn", "chonky", "fuzzy")	
```


---

The `__str__()` method is also built in. It gets called every time Python has to show a user-readable representation of an object, as with `print`. You can customize the string method to generate the text representation of your object that you want. In this example, the string method returns the name and species of the pet, "Nutmeg the dog."

--- 