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
```python3
key_value = eval(input())

kv = sorted(key_value.items())

print("Keys and Values sorted in alphabetical order by the key")

for i in kv:
    print(i, end=" ")
```

## Sample Output
<img width="1184" height="748" alt="image" src="https://github.com/user-attachments/assets/646e3ec9-9c82-4cd5-a3d3-cd8d6f8f6c43" />

## Result

Thus the python program to sort a dictionary and print is completed successfully.
