# List Operations in Python: Sum of List Items

## 🎯 Aim
To write a Python program that calculates the **sum of all elements** in a list.

## 🧠 Algorithm
1. Define a list of numbers.
2. Use Python’s built-in `sum()` function to calculate the total.
3. Print the result.

## 🧾 Program

# Input list from user
n = int(input("Enter number of elements: "))
lst = []

for i in range(n):
    num = int(input("Enter element: "))
    lst.append(num)

# Calculate sum
total = 0
for i in lst:
    total += i
    
print("Sum of elements:", total)

## Output
<img width="1919" height="960" alt="image" src="https://github.com/user-attachments/assets/d2527ecf-e554-47d0-97c4-2d38f3c9bd24" />

## Result
