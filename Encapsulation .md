# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    
    # Constructor to initialize private variables
    def __init__(self, length, breadth):
        self.__length = length
        self.__breadth = breadth

    # Method to display private variables
    def display(self):
        print("Length =", self.__length)
        print("Breadth =", self.__breadth)


# Create an object of the Rectangle class
obj = Rectangle(10, 5)

# Call the display method
obj.display()
```
## Output
<img width="478" height="252" alt="image" src="https://github.com/user-attachments/assets/3c44f92e-5978-431e-b1bb-9b2eb63cdca8" />

## Result
The above program has been executed successfully.
