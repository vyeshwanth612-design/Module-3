## Loops in Python: Palindrome Number Checker

## 🎯 Aim
To write a Python program that checks whether a given number is a **palindrome** using loops.

## 🧠 Algorithm
1. Get input from the user and assign it to a variable `num`.
2. Assign the value of `num` to a temporary variable `temp`.
3. Initialize a variable `rev` to 0 (used to store the reversed number).
4. Use a `while` loop to reverse the digits:
   - While `temp > 0`:
     - `rev = (10 * rev) + temp % 10`
     - `temp = temp // 10`
5. After the loop, compare `rev` with `num`:
   - If equal, print that the number is a palindrome.
   - Else, print that it is not a palindrome.

## 🧾 Program
```py
num = int(input())

temp = num
rev = 0

while temp > 0:
    rev = (10 * rev) + (temp % 10)
    temp = temp // 10

if rev == num:
    print("The number is a palindrome")
else:
    print("The number is not a palindrome")
```
## Output
<img width="750" height="265" alt="image" src="https://github.com/user-attachments/assets/3a19cbc5-0170-4da4-9ab4-e5f3fa9b2d84" />


## Result
The Python program was executed successfully, and the given number was checked using a loop. The program correctly determined whether the number is a palindrome or not.
