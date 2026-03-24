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
~~~
# Program to handle IndexError

list1 = [1, 2, 3, 4]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
~~~
## Output
<img width="520" height="222" alt="Screenshot 2026-03-24 142332" src="https://github.com/user-attachments/assets/8c621723-8cab-4436-83c8-c06ae0e2827c" />

## Result:
Thus, the Python program to handle an IndexError using exception handling was successfully executed and verified.
