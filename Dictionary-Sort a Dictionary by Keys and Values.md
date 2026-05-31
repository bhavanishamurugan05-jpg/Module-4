# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
d = {'c': 'cat', 'a': 'apple', 'b': 'ball'}

for key in sorted(d.keys()):
    print(key, ":", d[key])
```
## Sample Output
<img width="513" height="253" alt="image" src="https://github.com/user-attachments/assets/bf6448a3-4f1b-434b-bf49-198571009e39" />

## Result
Thus, the Python program successfully sorts the dictionary both by keys and by values using the sorted() function.
