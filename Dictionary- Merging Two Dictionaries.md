## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program

```
d1 = {'a': 10, 'b': 20}
d2 = {'c': 30, 'd': 40}

d1.update(d2)

print("Merged Dictionary:", d1)
```
## Output
<img width="765" height="193" alt="image" src="https://github.com/user-attachments/assets/835bd831-3d50-478a-8984-31228008268a" />

## Result
Thus, the Python program successfully merges two dictionaries using the ** unpacking operator, where values from the second dictionary overwrite duplicate keys from the first.
