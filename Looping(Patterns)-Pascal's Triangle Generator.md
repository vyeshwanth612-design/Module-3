# 🔺 Looping(Patterns)-Pascal's Triangle Generator in Python

This project demonstrates a simple Python program to generate **Pascal’s Triangle**, where the number of rows is provided by the user.

---

## 🎯 Aim

To write a Python program that generates **Pascal's Triangle** using numbers. The number of rows is accepted from the user.

---

## 🧠 Algorithm

1. Start the program.
2. Input the number of rows from the user.
3. Loop from 0 to the number of rows.
4. For each row:
   - Print appropriate spaces to shape the triangle.
   - Compute values using the formula:  
     \[
     C(n, k) = \frac{n!}{k!(n-k)!}
     \]
5. Print all rows of Pascal’s Triangle.
6. End the program.

---

## 🧪 Program
```py

n = int(input())

for i in range(n):
   
    for j in range(n - i - 1):
        print(" ", end="")

   
    num = 1
    for j in range(i + 1):
        print(num, end=" ")
        num = num * (i - j) // (j + 1)

    print()
```
## Sample Output
<img width="575" height="413" alt="image" src="https://github.com/user-attachments/assets/16198dfa-c88b-4c32-a942-332177027075" />



## Result
The Python program was executed successfully, and Pascal’s Triangle was generated correctly for the given number of rows using the appropriate mathematical logic.

