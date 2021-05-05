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

--- 

### Classes in Python
 
```py 
class Pet:
    def __init__(self, name, species):
        self.name = name
        self.species = species
    
    def __str__(self):
        return f'{self.name} the {self.species}'
```
---