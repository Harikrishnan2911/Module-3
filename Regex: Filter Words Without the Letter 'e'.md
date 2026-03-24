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

import re

# Input list
n = int(input("Enter number of elements: "))
lst = []

for i in range(n):
    word = input("Enter element: ")
    lst.append(word)

# Filter elements that do NOT contain 'e'
result = []
for item in lst:
    if not re.search('e', item):
        result.append(item)

print("Filtered list:", result)

## Output
<img width="1917" height="968" alt="image" src="https://github.com/user-attachments/assets/7e6d0f2c-4834-424f-b7f4-6fe10920d63a" />

## Result
