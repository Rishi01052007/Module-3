# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program
```python
items=[153,147,124,102]
print("The sum of the items in the list is ", sum(items))
```



## Output
![Screenshot 2025-04-30 103518](https://github.com/user-attachments/assets/aee49743-c56d-4a2e-8e7b-aa2ff25e11df)


## Result
Hence the program executed successfully!
# Regex in Python: Filter Words Without the Letter 'e'

## 🎯 Aim
To write a Python program that filters out and returns all elements from a list **that do not contain the letter `'e'`**, using **regular expressions (regex)**.

## 🧠 Algorithm
1. Import the `re` module.
2. Initialize an empty list `l1` to store results.
3. Define a list of words:  
   `items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']`
4. Iterate through each word in the list:
   - Use `re.search(r"e", i)` to check if the word contains `'e'`.
   - If **not**, append the word to `l1`.
5. Print the final filtered list.

## 🧾 Program
```python
import re
l1 = [] 
items = ['goal', 'new', 'user', 'sit', 'eat', 'dinner']
for i in items:
    if not re.search(r"e", i):  
        l1.append(i)  
print(l1)
```
## Output
![Screenshot 2025-04-30 104439](https://github.com/user-attachments/assets/9ecf5d41-cdd1-4ba6-99ee-2025abd01492)


## Result
Hence the program executed successfully!
# Module-3
# 🧹 Strings-Remove Nth Index Character from a String

## 🎯 Aim
To write a Python program that accepts a string and removes the character at a specified index.

## 🧠 Algorithm
1. Define a function named `remove` that takes the input string as an argument.
2. Read the index `n` from the user input.
3. Initialize an empty string `a` to store the new string.
4. Iterate over each index of the string using a `for` loop.
5. Check if the current index `i` is not equal to `n`.
6. If `i != n`, append the character at index `i` to string `a`.
7. After the loop, return the modified string `a`.
8. Print the final result.

## 💻 Program
```python
def remove(s):
    n = int(input())  
    a = "" 
    for i in range(len(s)):  
        if i != n:  
            a += s[i]  
    return a  
s = input("Enter a string: ") 
print("Modified string:", remove(s))
```
## Output
![Screenshot 2025-04-30 105126](https://github.com/user-attachments/assets/7ea81350-c50e-46dc-9586-931448cbac00)


## Result
Hence the program executed successfully!
# Strings-Palindrome Check in Python (Without Built-in Functions)

## 🎯 Aim
To write a Python program to check whether the string `"google"` is a **palindrome** or not, without using built-in palindrome checking functions.

## 🧠 Algorithm
1. Assign the string `"google"` to a variable.
2. Reverse the string manually using slicing (`[::-1]`).
3. Compare the original string with the reversed string.
   - If they are equal, print that the string is a palindrome.
   - Otherwise, print that it is not a palindrome.
4. Execute the program.

## 🧾 Program
```python

s = "google"
rev_s = s[::-1]
if s == rev_s:
    print(f'"{s}" is a palindrome.')
else:
    print(f'"{s}" is not a palindrome.')
```

## Output
![Screenshot 2025-04-30 105359](https://github.com/user-attachments/assets/ee4970c9-58bc-4f42-acbd-c38603008b94)


## Result
Hence the program executed successfully!
# Tuple in Python: Check Element Existence

## 🎯 Aim
To write a Python program that checks if the element `'n'` and the element `8` exist within a given tuple.

## 🧠 Algorithm
1. Define a tuple `x` with some letters and numbers.
2. Use the `in` operator to check if the string `'n'` exists within the tuple.
3. Use the `in` operator to check if the integer `8` exists within the tuple.
4. Print the results.

## 🧾 Program
```python
x = ("s", "8", "a", "v", "n", "g", "u", "r", "c", "e")
print('n' in x)
print('8' in x)
```

## Output
![Screenshot 2025-04-30 105645](https://github.com/user-attachments/assets/c1a6290b-17b4-44d3-ad65-5504f2fe900f)

## Result
Hence the program executed successfully!
