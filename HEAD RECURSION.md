# 🔁 Types of Recursion: Head Recursion in Python

## 🎯 AIM:
To write a Python program to demonstrate **Head Recursion** by finding and printing the sequence based on the sum of all digits (even or odd adjusted input).

## 🧠 ALGORITHM:

1. **Start**
2. Define a recursive function `fun(n)`
3. In the function:
   - Create a recursive call at the **beginning** (Head Recursion)
   - Print the result after the recursive call
4. Take input from the user
5. If input is odd, convert it to the next even number
6. Call the recursive function
7. **Stop**

## 💻 PROGRAM:

```python
def fun(n):
    if n == 0:
        return
    fun(n - 2)           # Head recursion (recursive call first)
    print(n, end=" ")

num = int(input())
if num % 2 != 0:         # If odd, convert to next even number
    num += 1
fun(num)
```


## OUTPUT

Input: 7
2 4 6 8

## RESULT

Thus, the Python program successfully demonstrates Head Recursion, printing the sequence after adjusting the input based on even or odd value.
