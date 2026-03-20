# Exp.No:21  
## Constructors - Parameterized Constructor

---

### AIM  
To write a Python code to create a class for a person with a parameterized constructor, which will take the `name` and `userid` of the person as parameters and print the `userid` of the person.

---

### ALGORITHM

1. Begin the program.  
2. Define a `person` class.  
3. The `person` class should have a parameterized `__init__` method that accepts two parameters: `name` and `userid`.  
4. Inside the `__init__` method, assign the `name` to `self.name` and the `userid` to `self.userid`.  
5. Print the `self.userid`.  
6. Prompt the user to enter their `name` (string) and `userid`.  
7. Create an instance `s1` of the `person` class by passing the entered `name` and `userid` to the constructor.  
8. Terminate the program.

---

### PROGRAM

```
REG NO- 212222060098
NAME : John christober T

class Person:
    def __init__(self, name, userid):
        self.name = name
        self.userid = userid
        print(self.userid)
name=input()
userid=input()
s1 = Person(name, userid)

```

### OUTPUT
<img width="342" height="112" alt="image" src="https://github.com/user-attachments/assets/0cc1d882-7c31-442e-ad3b-c9ba9e9f889f" />

### RESULT
Thus the Python code to create a class for a person with a parameterized constructor, which will take the name and userid of the person as parameters and print the userid of the person was implemented and executed successfully.
