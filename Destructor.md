# Exp.No:22  
## Destructor

---

### AIM  
To create a Python class `Student` with a destructor.

---

### ALGORITHM

1. Begin the program.  
2. Define the `student` class.  
3. Inside the `student` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `student` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name-  AISHWARYA K
class Employee:
    def __init__(self):
        print("Employee created.")

    def __del__(self):
        print("Destructor called, Employee deleted.")

obj = Employee()
del obj
```

### OUTPUT
<img width="684" height="168" alt="image" src="https://github.com/user-attachments/assets/b1765fa0-9fa8-4200-affa-c79d6e900146" />


### RESULT
Thus, the Python program to demonstrate the use of a destructor in a class has been successfully executed and the output is verified
