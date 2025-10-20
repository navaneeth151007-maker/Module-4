# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```c
filename = "sample.txt"
try:
    with open(filename, 'r') as file:
        count = 0
        for line in file:
            # Remove leading/trailing whitespaces and check first character
            if not line.strip().startswith('T'):
                count += 1
    print("Number of lines NOT starting with 'T':", count)
except FileNotFoundError:
    print("Error: File not found. Please check the file name.")

```
## Output
<img width="533" height="27" alt="image" src="https://github.com/user-attachments/assets/b39d23f0-da54-415f-b913-9aa75ea71c73" />

## Result
Thus, the program has been executed successfully.


