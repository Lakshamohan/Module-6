# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program
```

class Beans:
    def type(self):
        print("Vegetable")
    
    def color(self):
        print("Green")

class Mango:
    def type(self):
        print("Fruit")
    
    def color(self):
        print("Yellow")


def func(obj):
    obj.type()
    obj.color()
bean_obj = Beans()
mango_obj = Mango()
func(bean_obj)
func(mango_obj)
```
## Output
<img width="1291" height="647" alt="504742793-ac566111-d36d-4052-ac93-c6bc80f96344" src="https://github.com/user-attachments/assets/1410a09b-e911-4d7b-9e64-31059650ea85" />

## Result
Successfully wrote two specific classes — Beans and Mango. Then, create a generic function that can accept any object and determine its type (Fruit or Vegetable) and color, using polymorphism.
