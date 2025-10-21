# PYTHON MODULE - 5
# (B) Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🚀 Overview:

The program defines a class `Demo` with:

- A **constructor** `__init__` that initializes an instance variable and prints a message.
- A **destructor** `__del__` that prints a message when the object is destroyed.

## 🧠 Algorithm:

1. Define a class named `Demo`.
2. Inside the class, define the `__init__` method:
   - Initialize an instance variable `status` with the value `"Alive"`.
   - Print the value of `status`.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `Demo` class.
   - Delete the object using the `del` keyword.
## Program:

    class demo:
        def __init__(self):
            print("The Constructor is executing....")
            self.status = "Alive"
            print("The class is",self.status)
        
        def __del__(self):
            print("The Destructor is executing....")
            self.status = "Death"
            print("The class is",self.status)
    d = demo()
    del d

## 🧪 Output:

<img width="1918" height="700" alt="image" src="https://github.com/user-attachments/assets/81cb6d39-70e3-4885-b21a-611bbfdc19c9" />

## Result:

Thus, The Python program to demonstrates how to implement a **destructor** in Python using a simple class was executed successfully.

