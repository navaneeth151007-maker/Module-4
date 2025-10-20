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
```c
my_dict = {'apple': 3, 'banana': 1, 'cherry': 2}
sorted_by_keys = dict(sorted(my_dict.items()))
print("Original Dictionary:", my_dict)
print("Sorted by Keys:", sorted_by_keys)

```

## Sample Output
<img width="602" height="70" alt="image" src="https://github.com/user-attachments/assets/f664c0a9-1f7e-42c4-af58-562b15ef6df3" />


## Result
Thus, the program has been executed successfully.

