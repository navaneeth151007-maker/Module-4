# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```c
numbers = [10, 20, 30, 40, 50]
try:
    index = int(input("Enter index of element to access: "))
    print("Element at index", index, "is:", numbers[index])
except IndexError:
    print("Error: Index out of range. Please enter a valid index.")
except ValueError:
    print("Error: Please enter a valid integer index.")

```

## Output
<img width="393" height="52" alt="image" src="https://github.com/user-attachments/assets/84b073b6-979a-4264-bbda-905adaff85a7" />

## Result
Thus, the program has been executed successfully.

