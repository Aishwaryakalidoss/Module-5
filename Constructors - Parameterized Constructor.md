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
# Reg.No- 212222060008
# Name- AISHWARYA K
class Addition:
    def __init__(self, a, b):
        self.a = a
        self.b = b
        print("First number =", self.a)
        print("Second number =", self.b)

    def add(self):
        print("Addition of two numbers =", self.a + self.b)

a = int(input())
b = int(input())
obj = Addition(a, b)
obj.add()
```

### OUTPUT
<img width="684" height="279" alt="image" src="https://github.com/user-attachments/assets/d2cc1003-8c6e-4017-8aac-551ebbe62f10" />

### RESULT
Thus, the Python program to perform addition of two numbers using a parameterized constructor has been successfully executed and the output is verified.
