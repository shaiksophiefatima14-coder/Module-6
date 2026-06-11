# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program
```
class A:
    
    # Constructor
    def __init__(self, a):
        self.a = a

    # Overloading the < operator
    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"


# Create objects
ob1 = A(10)
ob2 = A(20)

# Use the overloaded < operator
print(ob1 < ob2)
```
## Output
<img width="436" height="212" alt="image" src="https://github.com/user-attachments/assets/c952d0a0-3bce-48e9-b4b3-fc8741a3e063" />

## Result
The above program has been executed successfully.
