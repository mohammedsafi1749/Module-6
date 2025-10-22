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
    class A:
        def __init__(self,a):
            self.a=a
        def __lt__(self,other):
           return self.a<other.a
    ob1 = A(2)

    ob2 = A(3)
    if ob2<ob1:
        print("ob2 is less than ob1")
    else:
        print("ob1 is less than ob2")
## Output
<img width="775" height="238" alt="image" src="https://github.com/user-attachments/assets/70758339-9764-457b-84e6-3d79c1e53f4e" />

## Result
Thus the program executed successfully .
