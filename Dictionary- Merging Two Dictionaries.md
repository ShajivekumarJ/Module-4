## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
~~~
# Program to merge two dictionaries

def merge(dict1, dict2):
    return {**dict1, **dict2}

# Define dictionaries
dict1 = {'a': 1, 'b': 2}
dict2 = {'b': 3, 'c': 4}

# Function call
result = merge(dict1, dict2)

# Output
print("Merged dictionary:", result)
~~~
## Output
<img width="524" height="201" alt="Screenshot 2026-03-24 141941" src="https://github.com/user-attachments/assets/deeb849a-4167-41dc-a3a6-a955ce6894c9" />

## Result
Thus, the Python program to merge two dictionaries using the ** unpacking operator was successfully executed and verified
