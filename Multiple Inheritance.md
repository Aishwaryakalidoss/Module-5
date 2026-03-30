# Exp.No:23  
## Multiple Inheritance

---

### AIM  
To write a Python program to get the name, attendance, and ID of a student and check if they are eligible for the next module using multiple inheritance. If attendance > 80, the student is eligible; otherwise, not eligible.

---

### ALGORITHM

1. Define the `Student` class.
2. Inside the `Student` class, define the `__init__` method (constructor). The `__init__` method accepts two parameters: `name` and `student_id`.
    - Inside the `__init__` method: Assign the value of `name` to `self.name` and `student_id` to `self.student_id`.
3. Define the `get_student_info` method inside the `Student` class:
    - This method should return a string formatted with `self.name` and `self.student_id`.
4. Define the `Attendance` class, which inherits from the `Student` class.
5. Inside the `Attendance` class, define the `__init__` method (constructor).
    - The `__init__` method accepts three parameters: `name`, `student_id`, and `attendance`.
    - Inside the `__init__` method: Call the parent class constructor `super().__init__(name, student_id)` to initialize `name` and `student_id`. Assign the value of `attendance` to `self.attendance`.
6. Define the `check_eligibility` method inside the `Attendance` class:
    - If `self.attendance` is greater than 80, return a formatted string indicating the student is eligible for the module exam.
    - Otherwise, return a formatted string indicating the student is not eligible for the module exam.
7. Prompt the user to enter the `name` (as a string), `student_id` (as an integer), and `attendance` (as an integer).
8. Create an instance `student` of the `Attendance` class, passing the entered `name`, `student_id`, and `attendance` to the constructor.
9. Call the `check_eligibility` method on the `student` object and print the result.
10. Terminate the program.

---

### PROGRAM

```
# Reg.No- 212222060008
# Name- AISHWARYA K
class Add:
    def __init__(self, a, b):
        self.a = a
        self.b = b
    def add(self):
        return self.a + self.b

class Sub:
    def __init__(self, a, b):
        self.a = a
        self.b = b
    def sub(self):
        return self.a - self.b

class Div:
    def __init__(self, a, b):
        self.a = a
        self.b = b
    def div(self):
        return self.a / self.b

class Calculate(Add, Sub, Div):
    def __init__(self, a, b):
        self.a = a
        self.b = b

a = int(input())
b = int(input())
obj = Calculate(a, b)
print(obj.add())
print(obj.sub())
print(obj.div())
```

### OUTPUT
<img width="406" height="200" alt="image" src="https://github.com/user-attachments/assets/5533261f-7875-476e-8cf5-24061ac7c43c" />


### RESULT
Thus, the Python program to calculate Addition, Subtraction and Division using Multiple Inheritance has been successfully executed and the output is verified.



