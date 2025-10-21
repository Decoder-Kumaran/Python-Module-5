# PYTHON MODULE - 5
# (E) Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim:

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm:

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program:

    class Calculation1:
        def Addition(self):
             return self.a + self.b
    class Calculation2:
        def Subraction(self):
             return self.a - self.b
    class Derived(Calculation1,Calculation2):
        def __init__(self,a,b):
            self.a = a
            self.b =b
        def Division(self):
            return self.a / self.b
    a  = int(input("Enter Number-1 : "))
    b = int(input("Enter Number-2 : "))
    derived = Derived(a,b)
    print("Addition of given two number is",derived.Addition())
    print("Subraction of given two number is",derived.Subraction())
    print("Division of given two number is",derived.Division())

## Output:

<img width="1917" height="916" alt="image" src="https://github.com/user-attachments/assets/1338bbf3-e58e-4b78-9e84-263e04cd2ee8" />

## Result:

Thus, The Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes was executed successfully.
