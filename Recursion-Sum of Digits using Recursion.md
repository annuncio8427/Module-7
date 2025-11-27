# # 🔁 Recursion:Sum of Digits using Recursion in Python

## 🎯 AIM:
To write a Python program to calculate the **sum of all digits** in a number using **recursion**.

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `sum_digit(n)` that:
   - Returns 0 if `n <= 0` (Base Case)
   - Else, returns `n % 10 + sum_digit(n // 10)` (Recursive Case)
3. Take integer input from the user.
4. Call the recursive function and store the result.
5. Print the result.
6. **Stop**

## 💻 PROGRAM:

def sum_digit(n):
    if n <= 0:
        return 0
    return n % 10 + sum_digit(n // 10)

num = int(input())
result = sum_digit(num)
print("Sum of digits:", result)


## OUTPUT

Input: 456
Sum of digits: 15

## RESULT
Thus, the Python program successfully calculates the sum of all digits in a number using recursion.
