# 🧾 List Comprehension:Generates all even numbers between 200 and 300
## 🎯 AIM:
To write a Python class-based program that generates all even numbers between 200 and 300 using **list comprehension**, and stores them in a list.

---

## 🧠 ALGORITHM:

1. **Start**
2. Create a class named `program`
3. Create variables `a`, `b`, and `c` to represent:
   - `a`: Lower limit
   - `b`: Step value
   - `c`: Upper limit
4. Initialize the values using a constructor `__init__`
5. Define a method `display()` that uses **list comprehension** to store even numbers
6. Print the resulting list of even numbers
7. **Stop**
---
## 💻 PROGRAM:
```
class program:
    def __init__(self, a, b, c):
        self.a = a 
        self.b = b 
        self.c = c 

    def display(self):
        evens = [x for x in range(self.a, self.c + 1, self.b) if x % 2 == 0]
        print(evens)

obj = program(200, 2, 300)
obj.display()

```
## OUTPUT:
<img width="819" height="299" alt="image" src="https://github.com/user-attachments/assets/4f1cd89f-b8ce-4ac8-99fb-2dc1a05e0097" />

## RESULT:
Thus, the program is executed successfully.
