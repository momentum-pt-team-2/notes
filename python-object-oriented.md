Object Oriented Programming
April 27, 2021

---

### Principles of Object Oriented Programming
- Abstraction
^ Abstraction means that external code is unconcerned with internal workings of a class
- Encapsulation
- Inheritance
- Polymorphism

---

### CRC Model
- Class
- Responsibilities
- Collaborators

[Explanation](http://www.agilemodeling.com/artifacts/crcModel.htm)
--- 

### Classes in Python
At a minimum, you will usually write custom `__init__` and `__str__` methods for your classes. If you don't write them, Python will default to the built-in methods my the same name. 

```py 
class Pet:
    def __init__(self, name, species):
        self.name = name
        self.species = species
    
    def __str__(self):
        return f'{self.name} the {self.species}'
```
---