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

# Given string
text = "google"

# Reverse using loop
reverse = ""

for ch in text:
    reverse = ch + reverse

# Check palindrome
if text == reverse:
    print("Palindrome")
else:
    print("Not a palindrome")

## Output
<img width="1919" height="968" alt="image" src="https://github.com/user-attachments/assets/ebfeac15-a1e6-4d98-8f48-bb7421b67c41" />

## Result
